from selenium import webdriver
from webdriver_manager.chrome import ChromeDriverManager

chrome_options = webdriver.ChromeOptions()
chrome_options.add_argument('--headless')
chrome_options.add_argument('--no-sandbox')
chrome_options.add_argument('--disable-dev-shm-usage')
chrome_options.add_experimental_option('excludeSwitches', ['enable-logging'])
chrome_options.add_argument('--log-level=3')

driver = webdriver.Chrome(
  ChromeDriverManager().install(), options=chrome_options)
  
driver.set_page_load_timeout(5)

driver.get('https://www.sofascore.com/football/livescore')

jogos = driver.find_elements_by_css_selector('*[class^="EventCellstyles__Link-sc-1speifn-0"] > *[class^="styles__InlineSvg-sc-buzci4-0 styles__IconPlayerStats-sc-buzci4-1"]')
                              
ps = browser.page_source
len(jogos)

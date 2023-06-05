
from selenium import webdriver
from selenium.webdriver.common.by import By

driver = webdriver.Chrome()
driver.maximize_window()
url_login = 'https://www.binance.com/pt-BR'
driver.get(url_login)
tempo=input('faça o login, vá a página de trade e aperte enter.')


preço = driver.find_element(By.XPATH, '//*[@id="__APP"]/div[2]/div/div/div[2]/div[2]/div/div[1]/div[2]/div[1]')
if driver.find_element(preço):
    print(preço)

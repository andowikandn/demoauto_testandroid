from appium import webdriver
from appium.webdriver.common.appiumby import AppiumBy
from appium.options.android.uiautomator2.base import UiAutomator2Options
from time import sleep

options = UiAutomator2Options()

options.udid = "127.0.0.1:62001"
options.platform_name = "Android"
options.app_package = "com.code2lead.kwad"
options.app_activity = "com.code2lead.kwad.MainActivity"

driver = webdriver.Remote('http://127.0.0.1:4723', options=options)

# click enter some value
driver.find_element(AppiumBy.ACCESSIBILITY_ID, 'Btn1') .click()
sleep(2)
# fill value
driver.find_element(AppiumBy.ID, 'com.code2lead.kwad:id/Et1').send_keys('Hello World')
sleep(1)
# click sumbit
driver.find_element(AppiumBy.ID, 'com.code2lead.kwad:id/Btn1').click()
sleep(1)
# back button
driver.find_element(AppiumBy.ACCESSIBILITY_ID, 'Navigasi naik').click()

# click contact form us
driver.find_element(AppiumBy.ACCESSIBILITY_ID, 'Btn2').click()
sleep(2)
# fill form 
driver.find_element(AppiumBy.ID, 'com.code2lead.kwad:id/Et2').send_keys('NAMA')
sleep(1)
driver.find_element(AppiumBy.ID, 'com.code2lead.kwad:id/Et3').send_keys('EMAIL')
sleep(1)
driver.find_element(AppiumBy.ID, 'com.code2lead.kwad:id/Et6').send_keys('email@mail.com')
sleep(1)
driver.find_element(AppiumBy.ID, 'com.code2lead.kwad:id/Et7').send_keys('08080909')
sleep(1)
# click submit   
driver.find_element(AppiumBy.ID, 'com.code2lead.kwad:id/Btn2').click()
sleep(1)
# back button
driver.find_element(AppiumBy.ACCESSIBILITY_ID, 'Navigasi naik').click()

# click tab
driver.find_element(AppiumBy.ACCESSIBILITY_ID, 'Btn4').click()
sleep(2)
# sport
driver.find_element(AppiumBy.ACCESSIBILITY_ID, 'Sport').click()
# movie
driver.find_element(AppiumBy.ACCESSIBILITY_ID, 'Movie').click()
sleep(1)
# home
driver.find_element(AppiumBy.ACCESSIBILITY_ID, 'Home').click()
sleep(1)
# back button
driver.find_element(AppiumBy.ACCESSIBILITY_ID, 'Navigasi naik').click()

# login button invalid user
driver.find_element(AppiumBy.ACCESSIBILITY_ID, 'Btn6').click()
sleep(2)
driver.find_element(AppiumBy.ID, 'com.code2lead.kwad:id/Et4').send_keys('email@mail.com')
sleep(2)
driver.find_element(AppiumBy.ID, 'com.code2lead.kwad:id/Et5').send_keys('1q1q')
sleep(1)
driver.find_element(AppiumBy.ID, 'com.code2lead.kwad:id/Btn3').click()
sleep(2)
# with valid user
driver.find_element(AppiumBy.ID, 'com.code2lead.kwad:id/Et4').send_keys('admin@gmail.com')
sleep(1)
driver.find_element(AppiumBy.ID, 'com.code2lead.kwad:id/Et5').send_keys('admin123')
sleep(1)
driver.find_element(AppiumBy.ID, 'com.code2lead.kwad:id/Btn3').click()
sleep(2)
# enter admin
driver.find_element(AppiumBy.ID, 'com.code2lead.kwad:id/Edt_admin').send_keys('This Admin')
sleep(1)
# submit
driver.find_element(AppiumBy.ID, 'com.code2lead.kwad:id/Btn_admin_sub').click()
sleep(1)

# back button
driver.find_element(AppiumBy.ACCESSIBILITY_ID, 'Navigasi naik').click()
sleep(1)
driver.find_element(AppiumBy.ACCESSIBILITY_ID, 'Navigasi naik').click()
sleep(1)

# click time
driver.find_element(AppiumBy.ACCESSIBILITY_ID, 'Btn8').click()
sleep(5)




### Issue 1: Improper behaviour of 'Handmade in the USA' hyperlink on the top bar.

**Category:** Navigation

**Severity:** Medium

**Full description:**

Upon clicking on said link user is taken to the 'Meet the staff' page. However each consecutive click adds '/pages/' to the address resulting in 404 error.
![obraz](https://github.com/lech-dabrowski/Portfolio-Web-application/assets/112244024/f8bcb297-e3f6-4335-8bd9-a39901dc9277)


**Reproduction steps:**

1. Navigate to the main page by either typing https://www.walkerscelticjewelry.com/ or clicking on a logo
2. Click on 'Handmade in the USA' hyperlink and observe proper behaviour.
3. Click for a second time to get corrupted address and 404 error.

---

### Issue 2: Broken hyperlink on 'Ring sizing chart' page

**Category:** Navigation

**Severity:** Minor

**Full description:**

'Ring sizing chart' page contains a hyperlink to an article 'Getting Her Ring Size Without Ruining the Surprise'. While the article exists and can be searched for, the link itself is broken and leads nowhere.

**Reproduction steps:**

1. From the main page, using Navigation Bar go to rings -> ring sizing chart
2. In the body of an article find a phrase 'Getting Her Ring Size Without Ruining the Surprise' which looks like a clickable hyperlink and click on it
3. Observe an error 404 message.

---

### Issue 3: Product pages having Google+ links

**Category:** Navigation

**Severity:** Minor

**Full description:**

Product pages contain links to various social media platforms among them is now defunct Google+. While not a serious issue, it is suggested to remove those links to avoid confusion.

**Reproduction steps:**

1. Open any product page by either navigating to it or choosing from the list of 'Featured products' on the the main page
2. On the right side, just under the product description, there is a collection of social media links
3. Click on 'Add to Google+' link, a page should appear explaining termination of Google+ service.

---

### Issue 0: 'About us' button on navigation bar is displayed in different line than other buttons.

**Category:** Visual

**Severity:** Medium

**Full description:**

'About us' button on navigation bar is displayed in different line than other buttons. Issue is present on all tested browsers, all resolutions higher than 1280 x 720 and all levels of zoom.
![obraz](https://github.com/lech-dabrowski/Portfolio-Web-application/assets/112244024/b1a6dace-2385-432d-a4e4-219bdeae353a)

**Reproduction steps:**

Navigation bar is always visible. Simply navigate to the top of the page.

---

### Issue 0: 'Certified Reviews' icon not appearing in Firefox

**Category:** Visual

**Severity:** Minor

**Full description:**

At the bottom of the page there's a widget displaying number of 'Certified reviews'. It consists of .png background and some formatted text. On Firefox browser it does not display properly. Please refer to screenshots below:

Chrome:
![1](https://github.com/lech-dabrowski/Portfolio-Web-application/assets/112244024/3be24b4d-c13e-4fc3-9d05-5ecd89bafc61)
Firefox:
![2](https://github.com/lech-dabrowski/Portfolio-Web-application/assets/112244024/979f285f-cf63-4599-b0ec-564bfa404745)


**Reproduction steps:**

Navigate to the bottom of the page.

---

### Issue 0: No information about Cookie Policy anywhere on a website

**Category:** Compliance

**Severity:** Critical

**Full description:**

Website stores user activity such as search history and contents of shopping cart in a cookie file. To check it open browser DevTools (F12 on Google Chrome) and navigate to 'Application' -> 'Storage' -> 'Cookies' to see if any files are stored. While not a legal advice, it is strongly suggested to add an Accept Cookie Policy section, as failure to do so may result in fines in many territories.

**Reproduction steps**

1. Open Google Chrome (exact steps may vary for different browsers) 
2. Click on three dots in the top right corner of the browser window and choose 'Settings'
3. Navigate to 'Privacy and Security' and choose 'Clear Browsing Data'
4. Make sure that 'Cookies and other site data' is checked and click on 'Clear Data'
5. Restart browser
6. Navigate to https://www.walkerscelticjewelry.com/
7. Observe whether Cookie Policy information appears


---
![underconstruction.png](https://2.bp.blogspot.com/-8J_UuUku6RQ/Uy4AGwDbhTI/AAAAAAAACd0/KiJoXRXpazM/s1600/Under_Construction.png)

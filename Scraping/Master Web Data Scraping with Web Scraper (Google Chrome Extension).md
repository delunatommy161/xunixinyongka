# Master Web Data Scraping with Web Scraper (Google Chrome Extension)

> **Web Scraper** is a free and beginner-friendly web scraping tool designed for non-technical users. With minimal configuration and a few clicks, you can extract data from websites such as Zhihu answer lists, Weibo trends, eCommerce product information, blog article lists, and more.

---

## Installing Web Scraper

### Online Installation

To install online, you need access to the Chrome Web Store and a network with VPN capabilities.

1. Visit the [Web Scraper Chrome Extension page](https://chrome.google.com/webstore/detail/web-scraper/jnhgnonknehpejjnehehllkliplmbmhn) and click **“Add to Chrome.”**

   ![Step 1](https://i-blog.csdnimg.cn/blog_migrate/ab3335cd686ba04d1f644057d30c135e.png)

2. In the pop-up box, click **“Add Extension.”**

   ![Step 2](https://i-blog.csdnimg.cn/blog_migrate/594c0fbc86eb5363ea5147430aa4bb3f.png)

3. Once installed, the Web Scraper icon will appear in the Chrome toolbar.

   ![Installed Icon](https://i-blog.csdnimg.cn/blog_migrate/bd3dea4753a3fdca1b1f320c7c55a0cc.png)

---

### Offline Installation

1. Open Chrome and navigate to `chrome://extensions/`. Drag the downloaded Web Scraper `.crx` file into the browser window and click **“Add Extension.”**

   ![Offline Installation](https://i-blog.csdnimg.cn/blog_migrate/b573b7ebb34156f35d580d7214b52184.gif)

2. Once installed, the Web Scraper icon will appear in the Chrome toolbar.

   ![Installed Icon](https://i-blog.csdnimg.cn/blog_migrate/bd3dea4753a3fdca1b1f320c7c55a0cc.png)

---

## Getting Started with Web Scraper

### Opening Web Scraper

1. For Windows, press `F12` (or `Fn+F12` on certain laptops).  
2. For Mac, press `Command + Option + I`.  
3. Alternatively, open Chrome settings → More Tools → Developer Tools.

   ![Open Developer Tools](https://i-blog.csdnimg.cn/blog_migrate/68b11583d8013ccf22db553acd59dca4.png)

4. The Developer Tools interface will open, showing the Web Scraper tab.

   ![Web Scraper UI](https://i-blog.csdnimg.cn/blog_migrate/e6bbc2885a27fe29f7b0d1bb005b5902.png)

---

### How Web Scraper Works

The web scraping process generally follows these steps:

1. **Start with a URL**: Begin with a webpage containing the data you need (e.g., an article list or a paginated list).
2. **Extract Data**: Navigate through links or elements to gather required information.
3. **Iterate**: Repeat the process for subsequent pages or levels.

---

### Core Web Scraper Features

1. **Create Sitemap**: Define a "sitemap" (your scraping plan) with a starting URL.  
   ![Create Sitemap](https://i-blog.csdnimg.cn/blog_migrate/33c6ecb8a99604754cd205dcfc4124e4.png)

2. **Selectors**: Define "selectors" to specify which elements on the page to scrape (e.g., titles, links, or content).  
   ![Selectors](https://i-blog.csdnimg.cn/blog_migrate/9fc01f6ce6e7b5b410fa39fb2799b6ae.png)

3. **Data Export**: Export scraped data as a CSV file for further analysis.  
   ![Export CSV](https://i-blog.csdnimg.cn/blog_migrate/34dab0fdd75d16622ff59be862fb9350.png)

---

## Practical Use Cases

### Example 1: Scraping hao123 Website Data

#### Objective: Extract website names and URLs from the highlighted section of the hao123 homepage.

1. Open the **hao123** homepage and launch Web Scraper in Developer Tools.  
2. Create a new sitemap, naming it `hao123`, and set the start URL to the hao123 homepage.  
   ![Sitemap Setup](https://i-blog.csdnimg.cn/blog_migrate/96a9a7dbaa91bafe7e2f28dc5cc8cbd5.png)

3. Add a selector with the type `Link` to extract both names and URLs.  
   ![Link Selector](https://i-blog.csdnimg.cn/blog_migrate/3402526ebb1fc08b5d7ce0d7f0075aed.png)

4. Select the desired section by clicking the relevant links on the webpage. Ensure the "Multiple" option is selected.  
   ![Select Links](https://i-blog.csdnimg.cn/blog_migrate/8188dc73b65e067d505447f43eb76c34.png)

5. Save the selector and export the data to CSV for analysis.

---

### Example 2: Scraping Zhihu Answers

#### Objective: Extract all answers, including the responder's name, likes, and content, from a Zhihu question.

1. Open the Zhihu question page and create a new sitemap with the start URL.  
   ![Zhihu Sitemap](https://i-blog.csdnimg.cn/blog_migrate/23147cac6d493c137278216abcdcc5f0.png)

2. Add a selector for answer elements using `Element scroll down` to handle the infinite scrolling behavior.  
   ![Element Scroll Down](https://i-blog.csdnimg.cn/blog_migrate/cedb8875bec65297d41a5daae98f8b7e.png)

3. Define sub-selectors for names, likes, and content within each answer.  
   ![Selectors Setup](https://i-blog.csdnimg.cn/blog_migrate/f13c4151eafc84ba1bdfe9f82d307214.png)

4. Perform the scrape and export the collected data as a CSV file.

---

### Advertisement: Simplify Web Scraping with ScraperAPI

**[ScraperAPI](https://www.scraperapi.com/?fp_ref=coupons)** takes the hassle out of web scraping. Automatically handle proxies, CAPTCHAs, and millions of requests. Extract data seamlessly from sites like Amazon, Google, and Walmart. Try it for free today! 👉 [ScraperAPI](https://www.scraperapi.com/?fp_ref=coupons)

---

## Conclusion

Web Scraper is a powerful tool for beginners and professionals alike. By automating data collection tasks, you can save time and effort while gaining valuable insights. Whether you're scraping eCommerce product data or analyzing social media trends, Web Scraper makes the process straightforward and efficient.

For advanced scraping needs, consider **[ScraperAPI](https://www.scraperapi.com/?fp_ref=coupons)** to enhance your efficiency further!

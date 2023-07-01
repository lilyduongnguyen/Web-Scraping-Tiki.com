## README

This README provides an overview and instructions for using the web scraping script to extract data from the e-commerce website Tiki.com. The script utilizes Python, Selenium, and BeautifulSoup libraries to gather information.

![Tiki.vn Logo](https://salt.tikicdn.com/ts/upload/e4/49/6c/270be9859abd5f5ec5071da65fab0a94.png)

### About Tiki.vn
Tiki.vn is a leading e-commerce company in Vietnam, specializing in end-to-end supply chain management and brand partnerships. It is the fastest-growing retail company in Vietnam and the most popular B2C e-commerce platform.

## Web Scraping Script
The provided Python script enables scraping of data from Tiki.vn. It utilizes the Selenium library for web automation and data extraction, and the BeautifulSoup library for parsing HTML content.

### Prerequisites
To run the script, ensure the following prerequisites are met:

- Python: The script requires Python 3.x to be installed.
- Selenium: Install the Selenium library using pip by running `pip install selenium` in the terminal.
- BeautifulSoup: Install the BeautifulSoup library using pip by running `pip install beautifulsoup4` in the terminal.
- ChromeDriver: Download the appropriate ChromeDriver executable compatible with your Chrome browser version from the official website: https://sites.google.com/a/chromium.org/chromedriver/downloads

### Setup and Usage
1. Download the provided script and save it with a `.py` extension, such as `tiki_scraping.py`.
2. Place the downloaded ChromeDriver executable in the same directory as the script.
3. Open the terminal or command prompt.
4. Navigate to the directory where the script is located.
5. Run the script by executing the following command: `python tiki_scraping.py`.
6. The script will initiate data scraping from Tiki.vn for each category and multiple pages (up to 5 pages per category).
7. The extracted data will be saved in a CSV file named `tiki_scraped_data.csv`, created in the same directory as the script.

### Customization and Limitations
- The script's `main_categories` list, located at the beginning of the script, can be modified to include additional categories or edit existing ones. Each category should have a "Name" and a "URL" field.
- By default, the script scrapes the first 5 pages for each category. If desired, you can adjust the range within the main scraping loop to scrape a different number of pages.
- Keep in mind that web scraping is subject to website policies and legal restrictions. Prior to scraping, review Tiki.vn's terms of service and adhere to any applicable regulations.

### Additional Information
Tiki.vn maintains a dynamic, innovative work culture and currently employs over 500 team members. The company has garnered investment from notable entities like Seedcom, CyberAgents Ventures, Sumitomo Corporation, and VNG Corporation.

### Categories Scraped
The script is pre-configured to scrape data from the following categories on Tiki.vn:
- Đồ Chơi - Mẹ & Bé
- Điện Thoại - Máy Tính Bảng
- Làm Đẹp - Sức Khỏe
-

 Điện Gia Dụng
- Thời trang nữ
- Thời trang nam
- Giày - Dép nữ
- Giày - Dép nam
- Túi thời trang nữ
- Túi thời trang nam
- Balo và Vali
- Phụ kiện thời trang
- Đồng hồ và Trang sức
- Laptop - Máy Vi Tính - Linh kiện
- Nhà Cửa - Đời Sống
- Bách Hóa Online
- Hàng Quốc Tế
- Thiết Bị Số - Phụ Kiện Số
- Voucher - Dịch vụ
- Ô Tô - Xe Máy - Xe Đạp
- Nhà Sách Tiki
- Điện Tử - Điện Lạnh
- Thể Thao - Dã Ngoại
- Máy Ảnh - Máy Quay Phim

## Conclusion
The provided script empowers you to efficiently scrape data from Tiki.vn and store it in a CSV file. Customize the script according to your specific needs or extend its functionality as required. Ensure compliance with website policies and legal requirements, and explore the vibrant and growing e-commerce ecosystem of Tiki.vn.

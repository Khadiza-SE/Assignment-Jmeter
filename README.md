**This project includes two JMeter test plans:**

**booking.jmx:** Simulates 120000 users logging in, creating a booking, and searching over a 12-hour period.

**dmoney.jmx:** Simulates deposits, send money, make payments, and withdrawals using multiple threads and CSV datasets.

**Prerequisites:**

JMeter
Java 
Git

**Running the Tests:**
command:Clone the repository:git clone https://github.com/your-username/repository-name.git
cd repository-name

**Run booking.jmx:**

Command:jmeter -n -t booking.jmx -l booking.jtl -e -o booking-report

**Run dmoney.jmx:**
Make sure deposit.csv, sendMoney.csv, payment.csv, and withdraw.csv are in the directory.

Command: jmeter -n -t dmoney.jmx -l dmoney.jtl -e -o dmoney-report

****Booking HTML performance reports:****
**Load test screenshot of request summery and statistics:** https://drive.google.com/file/d/12-tNBJRv4sNIw6lhME3IbAKdvXufwdek/view?usp=sharing

**Load test excel report:** https://docs.google.com/spreadsheets/d/1Z0EjxW05hhgZZffbuV1plIutbEy4-1pHPttD7Xq8Jc8/edit?usp=sharing

**Stress test screenshot of request summery and statistics:** https://drive.google.com/file/d/1n4aNFh02pZPEBHUgmx3Hg3HdctOX40tO/view?usp=drive_link

**Stress test excel report:** https://docs.google.com/spreadsheets/d/1n1snPoUdYwWpuXKPLodJkcXLzakJ8FEdhaiK812rY4A/edit?usp=drive_link 


****Dmoney HTML performance report:****
**Screenshot of request summery and statistics (HTML report):** https://drive.google.com/file/d/1MlK0Pj6CFCHnSngWBSrB51FkOU-wiLiE/view?usp=drive_link

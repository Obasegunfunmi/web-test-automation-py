# Selenium + Python Test Automation Framework 🚀

I built this project to practice designing a **scalable test automation framework** using Selenium and Pytest.  
The goal was to apply real-world QA practices: Page Object Model, reusable utilities, custom test scenarios, and CI/CD pipelines.  

This repo shows how I would approach automation in a professional environment, with a focus on maintainability and clear reporting.

---

## 📂 Project Structure
- `tests/` → test cases (UI, alerts, dropdowns, file uploads, login, etc.)
- `pages/` → Page Objects for better test organization
- `utils/` → driver setup and config
- `reports/` → pytest-html test reports

---

## ⚡ Features
- Automated **UI tests** with Selenium
- Page Object Model (POM) for clean structure
- Custom scenarios: dropdowns, alerts, file uploads
- Generates **HTML reports**
- CI/CD with GitHub Actions
- Headless mode support for pipelines

---

## 🛠️ Setup
```bash
git clone https://github.com/your-username/selenium-framework.git
cd selenium-framework
pip install -r requirements.txt

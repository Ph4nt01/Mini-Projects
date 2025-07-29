# Mini-Projects

A curated collection of small tools and utilities I’ve built. This repository will grow over time as I add new mini-projects and experiments.

---

## 📂 Projects

1. **tm-timer**  
   A simple Python CLI timer.  
   - Parse durations like `1h2m40s`  
   - Live countdown in your terminal  
   - Install via `pipx install tm-timer`  
   - Source: see the `tm-timer/` submodule  

2. [**FFF-FormFieldFinder**]
   A Python script that scans a web page for a login form and constructs a sample payload.  
   - Detects `<form>` fiels   
   - Colorized output in terminal  
   - Source: see the `FFF-FormFieldFinder/` submodule  

---

## 🚀 Getting Started

Clone this repo (with submodules) in one step:

```
git clone --recurse-submodules git@github.com:YourUsername/mini-projects.git
```

Or, if you already cloned without submodules:

```
git submodule update --init --recursive
```

---

## ⚙️ Usage

### tm-timer

1. Install from PyPI:
   ```
   pip install tm
   ```
2. Run:
   ```
   tm 1h2m40s
   ```

### FFF-FormFieldFinder

1. Install dependencies:
   ```
   pip install -r FFF-FormFieldFinder/requirements.txt
   ```
2. Run:
   ```
   cd FFF-FormFieldFinder
   python form_field_finder.py
   ```
3. Enter the target URL when prompted.

---

## 🤝 Contributing

1. Fork this repository  
2. Create a branch: `git checkout -b feature/my-new-tool`  
3. Commit your changes: `git commit -m "Add my new mini-project"`  
4. Push to your fork: `git push origin feature/my-new-tool`  
5. Open a Pull Request  

Please keep each mini-project self-contained in its own directory, and include a README or doc string explaining its purpose and usage.

---

## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.



---

# 📰 Live News App - React (Class Based)

A real-time news application developed using **React.js**. This application fetches live headlines from various news sources globally using an external API. It features category-wise news browsing, pagination, and a smooth user experience with loading states.

## 🌟 Key Features

* **Category-Specific News:** Navigate through various sections like Business, Sports, Technology, Science, Health, and Entertainment.
* **Dynamic Routing:** Implemented using `react-router-dom` to switch categories without page reloads.
* **Real-time Data:** Fetches the latest news articles including title, description, author, and publication date.
* **Pagination:** Built-in "Next" and "Previous" buttons to explore multiple pages of news articles.
* **Interactive UI:** Modern card-based layout using **Bootstrap 5** for a responsive design.
* **Loading Spinner:** A dedicated Spinner component that appears while news data is being fetched from the API.

## 🛠️ Tech Stack

* **Frontend:** React.js (Class-based Components)
* **Styling:** Bootstrap 5 (CSS)
* **State Management:** Component State (this.state)
* **API Handling:** Fetch API with `async/await`
* **Routing:** React Router DOM

## 📂 Project Structure

```text
src/
├── components/
│   ├── Navbar.jsx      # Navigation bar with category links
│   ├── Newspage.jsx    # Main logic for fetching data and mapping articles
│   ├── Newsitems.jsx   # Reusable card component for individual news
│   └── Spinner.jsx     # Loading animation component
├── App.js              # Routing configuration and main entry point
└── index.js            # React DOM rendering

```

## 🚀 Installation & Setup

1. **Clone the Repository:**
```bash
git clone https://github.com/Premkumar5861/Live-News-App.git

```


2. **Navigate to Folder:**
```bash
cd Live-News-App

```


3. **Install Dependencies:**
```bash
npm install

```


4. **Add your API Key:**
Open `Newspage.jsx` and replace the placeholder API key with your own from [NewsAPI.org](https://newsapi.org/).
5. **Run the App:**
```bash
npm start

```



## 💡 Important Notes

* **API Limit:** If you are using the free tier of NewsAPI, please note that it might not work in a production/live environment (like GitHub Pages) due to their CORS policy for free accounts. It works perfectly on `localhost`.
* **Routing:** Each route in `App.js` uses a unique `key` prop. This ensures that React re-mounts the component and fetches new data when you switch categories.

---


Unga `App.js`-la neenga `key` props use pannirukeenga (e.g., `key="sports"`). Adhu romba nalla practice! Adhu dhaan category maathum pothu data-va refresh panna help pannum.

**Indha README detailed-ah irukka? Vera ethavathu points add pannanuma?**

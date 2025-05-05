# 🌿 CarbonWise: Track, Reduce, Sustain

## 🌍 Inspiration

The growing concern over climate change and the lack of accessible tools for individuals to measure their environmental impact inspired us to create **CarbonWise**. Many people want to make sustainable choices but struggle to track their carbon footprint effectively. We wanted to build an intuitive and user-friendly platform that empowers individuals to take action toward a greener future.

---

## ⚡ What It Does

CarbonWise allows users to calculate their carbon footprint either manually or by using **AI-powered image recognition** through the **Google Vision API**.

Users can:
- Take pictures of items, and the app identifies them.
- Receive estimated carbon footprints based on pre-defined categories.
- Track emissions across various sectors—**transportation, food, energy**, and more.
- Visualize their impact over time and make informed decisions to reduce their footprint.

---

## 🛠 How We Built It

- **Frontend:** Built using **React Native** for a seamless and responsive mobile experience.
- **Backend:** Built with **Node.js** to handle user authentication, data storage, and API requests.
- **AI Integration:** Utilized **Google Vision API** to analyze images, extract relevant text, and identify objects for footprint estimation.
- **Database:** Used **Firebase** to store user data, track historical footprints, and generate trends.
- **Data Processing:** Mapped Google Vision API results to estimated carbon footprints based on pre-defined categories.

---

## 🚧 Challenges We Ran Into

1. **Google Vision API Accuracy** – Ensuring object recognition results matched relevant carbon footprint estimates.
2. **Mapping Identified Objects to Carbon Data** – Since Google Vision API doesn’t provide carbon data directly, we created a custom mapping system.
3. **User Engagement** – Balancing simplicity with meaningful insights to keep users motivated.
4. **Performance Optimization** – Managing image recognition and real-time calculations without slowing down the app.

---

## 🏆 Accomplishments That We're Proud Of

- Successfully integrated **Google Vision API** for automated object detection and footprint calculation.
- Developed a smooth and intuitive UI that simplifies sustainability tracking.
- Created a robust system to track carbon impact across multiple categories.
- Overcame API-related limitations to deliver meaningful and actionable recommendations.

---

## 📚 What We Learned

- How to integrate and optimize APIs for real-world applications.
- Techniques for mapping object recognition results to meaningful sustainability data.
- The importance of balancing AI automation with manual input for a better user experience.
- Best practices for designing engaging and informative sustainability apps.

---

## 🚀 What's Next for CarbonWise

- Improve object recognition accuracy by refining mapping.
- Expand category and product support for better insights.
- Add a **community feature** to share sustainability tips and goals.
- Implement a **reward system** to encourage eco-friendly habits.
- Explore **web** and **smartwatch** versions for wider accessibility.

CarbonWise is just the beginning of a movement toward more conscious living. By leveraging AI and real-time tracking, we aim to empower users with the knowledge and tools to make a tangible impact in reducing their carbon footprint. 🌱

---

## 🧪 Run Instructions

On the /backend directory
1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
    node app.js
   ```

On the /frontend directory
1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
    npx expo start --clear
   ```

---

## 🧰 Built With

- [React Native](https://reactnative.dev/)
- [Node.js](https://nodejs.org/)
- [Firebase](https://firebase.google.com/)
- [Google Vision API](https://cloud.google.com/vision)
- [Axios](https://axios-http.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [Gemini](https://deepmind.google/technologies/gemini/)

---

## 📄 License

[MIT](LICENSE)


## Money Tracker App

## Description
This project is a **Money Tracker App** that allows users to record and track their **income and expenses**. The app provides a simple form to input financial data and stores it in a **MongoDB database** using **Node.js and Express.js**.

## Features
- Add **income and expenses**.
- Store financial records in **MongoDB**.
- Display a list of transactions.
- Calculate the total amount dynamically.
- User-friendly interface.

## Technologies Used
### Frontend
- **HTML**
- **CSS**
- **JavaScript**

### Backend
- **Node.js**
- **Express.js**
- **MongoDB**
- **Mongoose**
- **Body-parser**

## Installation & Setup
### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)

### Steps to Run
1. Clone the repository:
```sh
git clone https://github.com/your-repository/money-tracker.git
cd money-tracker
```
2. Install dependencies:
```sh
npm install
```
3. Start MongoDB (if not running already):
```sh
mongod
```
4. Run the server:
```sh
node server.js
```
5. Open your browser and go to:
```
http://localhost:5000/
```


## API Routes
| Route      | Method | Description |
|------------|--------|-------------|
| `/`        | GET    | Serves the home page |
| `/add`     | POST   | Adds a new income/expense record to MongoDB |

## Demo Video

[Watch the Demo Video](https://github.com/Punith-b2004/moneytracker-project/raw/main/public/moneytracker.mp4)


[Youtube link:](https://youtu.be/TR2KzQkT5tE?si=UGqMSAw3FWsdN8FP)




## Future Enhancements
- Implement **data visualization** for better financial insights.
- Add **user authentication** to store personalized data.
- Enable **data export** to CSV or PDF.

## Author
**Punith**

## License
This project is open-source and available under the [MIT License](LICENSE).


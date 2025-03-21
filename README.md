# Flutter IP Address Reputation Checker

**Overview**

This is a Flutter application that checks the reputation of an IP address using the IPQualityScore API. The app fetches the user's IP address and retrieves fraud-related details such as ISP name and fraud score.


**Tech Stack**

Frontend: Flutter (Dart)

API Services: http package for API requests

State Management: Stateful Widgets



**Setup Instructions**

***Prerequisites***

- Install Flutter by following the official Flutter installation guide.

- Obtain an API key from IPQualityScore.

***Installation Steps***

- Clone the repository
```git clone <repository-url>```

- Navigate to the project directory
```cd flutter_ip_reputation```

- Get the dependencies
```flutter pub get```

- Run the application
```flutter run```

**Usage**

- Open the app.

- Click the GET IP address reputation button.

- The app retrieves your public IP address.

- It fetches and displays reputation details such as ISP and Fraud Score in a pop-up dialog.

**API Integration**

 The app makes API requests to:

- https://api.ipify.org → Fetches the user's IP address.

- https://ipqualityscore.com/api/json/ip/{YOUR_API_KEY}/{IP_ADDRESS} → Retrieves IP reputation details.

##### Note: Ensure you replace ```{YOUR_API_KEY}``` with your actual API key from IPQualityScore

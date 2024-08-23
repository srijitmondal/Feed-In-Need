![githu](https://i.postimg.cc/WbF241g0/FIN.png)
<h1 align="center">Feed <img src="https://i.postimg.cc/9fy2WHYY/giphy.webp" width=100 /> in Need</h1>

Feed_In_Need is an Android-based platform aimed at connecting consumers who wish to donate surplus food with NGOs that are ready to accept and distribute it to those in need. The project consists of two interconnected applications, **FinCos** (for consumers) and **FinCept** (for NGOs), which communicate using Firebase to manage food donation pickup requests.

## Project Overview

In many communities, surplus food often goes to waste due to a lack of convenient channels for donation. Feed_In_Need aims to solve this issue by creating a seamless connection between those with surplus food and organizations that can distribute it. With a user-friendly interface and real-time updates, the app simplifies the process of donating and collecting food.

### Components

1. **FinCos**: The application for consumers who want to donate food. They can easily log in, input details about the food, and send pickup requests to nearby NGOs.

   - [FinCos GitHub Repository](https://github.com/srijitmondal/FinCos)

2. **FinCept**: The application for NGOs that will accept food donations. NGOs can view donation requests, confirm pickups, and manage their operations from this app.

   - [FinCept GitHub Repository](https://github.com/srijitmondal/FinCept)

### Key Features

- **Firebase Integration**: Real-time communication between consumers and NGOs for pickup requests.
- **User Authentication**: Secure login and registration system.
- **Seamless Communication**: Instant notification system for managing donation pickups.
- **Interactive Interface**: Easy-to-use design for both consumers and NGOs.

## How It Works

1. **Consumer Side (FinCos):**
   - A user logs in to the FinCos app.
   - They enter details about the food they wish to donate (type, quantity, etc.).
   - A pickup request is generated and sent to nearby NGOs through Firebase.

2. **NGO Side (FinCept):**
   - Registered NGOs receive pickup requests in the FinCept app.
   - They can accept or decline the request based on availability.
   - Upon accepting, the NGO can coordinate with the consumer for a convenient pickup time.

## Future Enhancements

- **Geo-Location Tracking**: To help NGOs locate donors more effectively.
- **Donation History**: Allowing users and NGOs to view past donations and pickups.
- **Feedback System**: Enabling better communication and service improvement.

## Contributing

We welcome contributions! Please feel free to submit issues, create pull requests, or reach out with any suggestions to enhance the project.

## License

This project is licensed under the MIT License.

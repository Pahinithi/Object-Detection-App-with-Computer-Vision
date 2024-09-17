# Object Detection App using TensorFlow.js and React.js

This **Object Detection App** is built using **TensorFlow.js** and **React.js**. The app enables real-time object detection using the **COCO-SSD** model, which can recognize and detect 80 different classes of objects in images or live webcam feeds. The user interface is designed using **Bootstrap** for a sleek, responsive design with a modern look.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [How to Run the App](#how-to-run-the-app)
- [Project Structure](#project-structure)
- [Screenshots](#screenshots)
- [How it Works](#how-it-works)
- [UI/UX Design](#uiux-design)
- [Contributing](#contributing)
- [License](#license)

## Demo

Check out the live demo of the Object Detection App:  
[Live Demo Link](https://drive.google.com/file/d/1uaz07KguQwrR0THQzPugip3ieT-ohHi2/view?usp=sharing)  

## Features

- **Real-time object detection** using the **COCO-SSD** model powered by **TensorFlow.js**.
- **Webcam integration** for real-time object detection or image file uploads.
- **Responsive design** with Bootstrap for a modern and clean user experience.
- **Instant object classification** with bounding boxes drawn around detected objects.
- **User-friendly interface** for ease of use and seamless experience.

## Technologies Used

- **React.js**: A JavaScript library for building user interfaces.
- **TensorFlow.js**: A machine learning library for JavaScript, used for loading the COCO-SSD model for object detection.
- **COCO-SSD Model**: A pre-trained object detection model to identify 80 different classes.
- **Webcam.js**: A library used for integrating webcam video feeds.
- **Bootstrap**: For a responsive, sleek, and modern UI design.
- **HTML5/CSS3**: For structuring and styling the web pages.

## How to Run the App

### Prerequisites

Ensure that you have **Node.js** and **npm** (or **yarn**) installed on your machine.

1. Clone the repository:

   ```bash
   git clone https://github.com/Pahinithi/Object-Detection-App-with-Computer-Vision
   ```

2. Navigate to the project directory:

   ```bash
   cd object-detection-app
   ```

3. Install the required dependencies:

   ```bash
   npm install
   ```

   or if you use yarn:

   ```bash
   yarn install
   ```

4. Start the React development server:

   ```bash
   npm start
   ```

   or:

   ```bash
   yarn start
   ```

5. Open your browser and visit `http://localhost:3000` to see the app in action.

## Project Structure

```bash
Building an Object Detection App/
├── public/
│   ├── favicon.ico
│   ├── index.html            # Main HTML file
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
├── src/
│   ├── App.css               # App-level CSS styles
│   ├── App.js                # Main React component for handling object detection
│   ├── index.css             # Global CSS styles
│   ├── index.js              # Entry point for React app
│   ├── utilities.js          # Utility functions for drawing bounding boxes
├── package.json              # Project dependencies and scripts
├── yarn.lock                 # Lockfile for yarn dependencies
├── package-lock.json         # Lockfile for npm dependencies
└── README.md                 # This file
```

### Key Files

- **`App.js`**: Main React component where the TensorFlow.js model is loaded, and object detection is performed.
- **`utilities.js`**: Contains helper functions like `drawRect` to draw bounding boxes around detected objects on the canvas.
- **`index.html`**: Main HTML file, includes Bootstrap and layout for the app.
- **`App.css`**: Contains the custom styling for the app.

## Screenshots

<img width="1728" alt="Screenshot 2024-09-15 at 16 33 54" src="https://github.com/user-attachments/assets/61275a8f-b269-491a-ae83-7056511828e6"> <br>


<img width="1728" alt="CV06" src="https://github.com/user-attachments/assets/cac0582c-bd90-42c5-a460-2da980459398">


## How it Works

1. The user opens the app, which activates the webcam using **Webcam.js** or allows for uploading an image.
2. **TensorFlow.js** loads the **COCO-SSD** model asynchronously, which is capable of detecting objects in real-time.
3. Once the model is loaded, it processes the video feed or image to detect objects and their positions.
4. Bounding boxes are drawn around detected objects in real-time on the **canvas** using the `drawRect` function from `utilities.js`.

## UI/UX Design

The design utilizes **Bootstrap 4.5.2** to provide a responsive and visually appealing layout. The background features a **linear gradient** of pastel colors—**#c3d8f7**, **#f7cdd0**, and **#fce8e8**—to create a calm and soothing visual experience. The main content is centered in a **glassy** container with a slight transparency, rounded corners, and a subtle box shadow to give a modern feel.

### Key UI Elements

- **Header**: Displays the app's title.
- **Instructions**: Brief explanation of how to use the app.
- **Start Detection Button**: Clickable button to initiate the object detection process.
- **Webcam Feed**: Real-time video feed captured using the webcam.
- **Canvas Overlay**: Displays bounding boxes around detected objects on top of the webcam feed.

## Contributing

Contributions are welcome! If you have suggestions for improvements, feel free to fork the repository, create a new branch, and submit a pull request.


## License

This project is licensed under the **MIT License**. 

## Contact

For any questions or support, please contact:

- **Name**: Pahirathan Nithilan
- **Email**: [nithilan32@gmail.com](mailto:nithilan32@gmail.com)
- **GitHub**: [Pahinithi](https://github.com/Pahinithi)

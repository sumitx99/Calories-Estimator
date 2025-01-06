# 🍲Calorie Estimator from Image

This project is a Streamlit-based web application that estimates the calorie content of food items in an uploaded image. It utilizes image recognition to identify food items and a nutrition database to fetch the calorie information.

## ✨Features

- **Image Upload**: Upload images of food items.
- **Food Detection**: Automatically detect food items in the uploaded image using an image recognition API.
- **Calorie Estimation**: Retrieve calorie information for the detected food items from a nutrition API.
- **User-Friendly Interface**: Built with Streamlit for an easy-to-use, interactive interface.

##  🛠️Technologies Used

- **Streamlit**: For the web application frontend.
- **Python**: Backend logic.
- **PIL (Python Imaging Library)**: To handle image uploads.
- **Image Recognition API**: Used to identify food items from images (replace with the actual API you choose).
- **Nutrition API**: To fetch calorie information (replace with the actual API you choose).

## Installation
**Install Dependencies**:
   
   Ensure you have Python installed. You can install the required packages using:


```bash
pip install -r requirements.txt
```

**Set Up Environment Variables**:

```bash
GOOGLE\_API\_KEY=your\_google\_api\_key
```

**Run the Application**:
```bash
streamlit run app.py
```


## 🧐How It Works

1. **Upload an Image**: Users upload an image containing food items.
2. **Image Recognition**: The image is sent to an image recognition API to detect food items.
3. **Calorie Retrieval**: Detected food items are sent to a nutrition API to retrieve their calorie content.
4. **Display Results**: The application displays the calorie breakdown of each food item and the total calorie count.

## 🖼️Screenshots

![App Screenshot](https://i.ibb.co/17ffxBg/Screenshot-2025-01-06-193939.png[/img][/url])

![App Screenshot](https://i.ibb.co/74xbZkf/Screenshot-2025-01-06-193956.png[/img][/url])

## 🌟 Future Enhancements

- Improve accuracy by integrating more sophisticated image recognition models.
- Include additional nutritional information like macronutrient breakdown.
- Allow manual input of portion sizes for more accurate calorie estimation.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.


## License

[This project is licensed under the MIT License. See the `LICENSE` file for more details.](https://github.com/sumitx99/Calories-Estimator/blob/main/LICENSE)


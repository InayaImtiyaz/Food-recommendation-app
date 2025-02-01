# **MealFit**

MealFit is an AI-powered meal recommendation system designed for university students. It provides personalized meal suggestions based on dietary preferences and health conditions such as diabetes, high blood pressure, and allergies. The app features an AI chatbot that helps users filter meals by ingredients they want to avoid.

## **Features**

AI Chatbot: Ask meal-related questions and get responses powered by OpenAI's GPT.

Personalized Recommendations: Filter meals based on dietary needs and health conditions.

Ingredient Exclusion: Avoid meals containing specific ingredients.

Meal Information: Displays meal images, ingredients, and health benefits.

## **Installation**

To run MealFit locally, follow these steps:

Clone the repository:

git clone https://github.com/yourusername/mealfit.git

Navigate to the project directory:

cd mealfit

Install dependencies:

pip install -r requirements.txt

Set up your OpenAI API key:

Replace openai.api_key in the script with your actual OpenAI API key.

Run the Streamlit app:

streamlit run app.py

## **Dependencies**

This project requires the following Python libraries:

streamlit

openai

pandas

Install them using:

pip install streamlit openai pandas

## **Usage**

Launch the app with streamlit run app.py.

Enter dietary preferences and ingredients to avoid in the sidebar.

Browse recommended meals with images and descriptions.

Use the AI chatbot to ask meal-related questions.

## **Future Enhancements**

Integration with a nutrition API for detailed meal analysis.

User authentication for saving preferences.

Expansion of meal database with more diverse options.

## **License**

This project is open-source under the MIT License.

## **Warning**

🚨 Do not expose your OpenAI API key in public repositories! Remove it from the code and use environment variables instead.

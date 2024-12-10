---

# SageMaker-Make Anything Bot

## Project Overview

The **SageMaker-Make Anything Bot** is an AI-powered chatbot designed to enhance the customer experience on e-commerce websites. This solution assists customers in efficiently finding and purchasing items for various projects, whether it's a food item, industrial product, or DIY project. By addressing the challenges faced by customers in online retail environments, our chatbot provides a seamless shopping experience through personalized recommendations and real-time assistance.

## Problem Statement

Customers of large retail stores often struggle to efficiently find and purchase items needed for their projects. This leads to frustration and a poor shopping experience due to:
- Lack of a unified platform for product search, in-store navigation, and tutorials.
- Difficulty in accessing relevant recommendations and managing their shopping cart.

## Solution

To tackle these challenges, we have developed a sophisticated AI-powered chatbot that utilizes advanced technologies:
- **Gemini 1.5 Pro Vision LLM** for understanding and processing user inputs in text and visual formats.
- **ChromaDB** for similarity search, providing accurate and relevant product recommendations.
- **Streamlit** for a user-friendly chatbot interface that integrates seamlessly with our self-created Django-based e-commerce website.

The bot offers a comprehensive solution, from finding project requirements on website to managing the shopping cart and providing solutions and tutorials for consumers to help them make whatever they want.

## Key Features

- **Interactive Chatbot Interface**: Built with Streamlit for an engaging user experience.
- **Personalized Recommendations**: Uses Generative AI and vector databases to enhance purchase intent.
- **Improved Engagement**: Achieved a 35% uplift in user interaction and a 15% increase in sales through intelligent recommendation algorithms.
- **In-Store Navigation**: Provides customers with the locations of items in nearby retail stores.

## Technology Stack

- **AI & Machine Learning**: Google Gemini Generative AI
- **Web Development**: Django (self-created e-commerce website), Streamlit, HTML, CSS, JavaScript
- **Database**: SQLite, ChromaDB

## Installation Instructions

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd SageMaker-Make-Anything-Bot
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up the database:
   - Follow the instructions in `database_setup.md` to configure your SQLite database.

4. Run the application:
   ```bash
   python app.py
   ```

## Usage

- Navigate to the chatbot interface in the ecommerce website(Self made-->code in the repo).
- Enter your project requirements, and the bot will provide relevant product suggestions.
- The bot will help manage your shopping cart and offer tips on what to add or not forget.

## Project Video

For a demonstration of the SageMaker-Make Anything Bot, please watch the project video here: [Project Video Link](<https://youtu.be/Vm9a1Mh63VU>).






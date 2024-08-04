<h1> AI Stock Advising ChatBot</h1>


<p>  This repository contains code to build an AI stock advising chatbot, integrating LangChain and OpenAI for reliable financial insights.</p>
<h2></h2>
<p><strong> Features:</strong> Precise information, Interactive Visualizations, Future stock price forecasting, Real time data, Risk assessment analysis</p>
<h2>Motivation</h2>
<p>  General purpose chatbots like ChatGPT may not offer reliable financial advice due to limitations in handling real-time data and numerical accuracy. Effective stock trading advice requires precise and up-to-date information. LLMs are great at processing text. Financial applications like Yahoo Finance and Google Stock News are known for their reliable real-time financial data.</p>

<p>  Our approch aims to build a solution that can combine reliable real time data from financial applications with great text processing capabilities of LLMS</p>
<h2>Sample Input and Output </h2>
<p><strong>User :</strong> Show me the historic stock price change of NVIDIA stock </p>
<p><h3>Response :</h3>
<p>The historic price of Nvidia is :</p>

  ![Flower](https://github.com/nandapg0204/AI_Stock_Advising_ChatBot/blob/main/images/nvidia.png?raw=true)
  
<p><strong>User :</strong> How does apple stock looks like for next 10 days </p>
<p><h3>Response :</h3>
The predicted Apple stock prices for the next 10 days are as follows:<br>  
- Day 1: $219.59<br>  
- Day 2: $219.50<br>  
- Day 3: $219.50<br>  
- Day 4: $219.56<br>  
- Day 5: $219.66<br>  
- Day 6: $219.78<br>  
- Day 7: $219.92<br>  
- Day 8: $220.07<br>  
- Day 9: $220.24<br>  
- Day 10: $220.41<br>
The stock price is predicted with  4.23% error.
</p>


<p><h3>User :</h3> What is the current price of Google stock </p>
<p><h3>Response :</h3>
The current price of Google stock (GOOG) is $168.40.</p>


<p><h3>User :</h3> Give me a stock name which i should not invest with an example and why(Show the details) </p>
<p><h3>Response :</h3>
A stock often advised against is GameStop (GME). It has high volatility, a trailing P/E ratio of 263.38, and significant debt, making it a risky investment.</p>
<p><h3>User :</h3> Give me the basic details of the Tokyo stock </p>


<p><h3>Response :</h3>
I couldn't find any information on Tokyo stock. Please check the name or provide a different stock.</p>




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <div style="max-width: 800px; margin: 0 auto; padding: 20px; font-family: Arial, sans-serif; line-height: 1.6;">
        <h1>Chatbot Sample Input & Output</h1>
        <div style="border: 1px solid #ddd; border-radius: 5px; padding: 10px; margin: 20px 0; background-color: #f9f9f9;">
            <div style="margin-bottom: 10px;">
                <p style="margin: 0; padding: 5px; border-radius: 5px; background-color: #e7f0ff; font-weight: bold; color: #007bff;">
                    <strong>User:</strong> What is the weather like today?
                </p>
            </div>
            <div style="margin-bottom: 10px;">
                <p style="margin: 0; padding: 5px; border-radius: 5px; background-color: #d4edda; font-weight: bold; color: #28a745;">
                    <strong>Bot:</strong> The weather is sunny with a high of 75°F (24°C).
                </p>
            </div>
            <div style="margin-bottom: 10px;">
                <p style="margin: 0; padding: 5px; border-radius: 5px; background-color: #e7f0ff; font-weight: bold; color: #007bff;">
                    <strong>User:</strong> Can you set a reminder for my meeting at 3 PM?
                </p>
            </div>
            <div style="margin-bottom: 10px;">
                <p style="margin: 0; padding: 5px; border-radius: 5px; background-color: #d4edda; font-weight: bold; color: #28a745;">
                    <strong>Bot:</strong> Sure, I've set a reminder for your meeting at 3 PM.
                </p>
            </div>
        </div>
    </div>
</body>
</html>

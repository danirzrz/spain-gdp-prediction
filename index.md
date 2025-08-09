
# 📊 Predicting Spain’s Economic Future with Data Science

**Can data science help us understand and forecast the economic future of a country?**  
In this project, I explored key indicators from the World Bank to analyze and predict Spain’s GDP using machine learning. Here's what I discovered.

---

## 🔍 What drives Spain’s GDP?

After cleaning and analyzing the dataset, I identified several indicators that strongly influence GDP. Among them, **life expectancy**, **school enrollment**, and **urban population growth** stood out. These features reflect long-term investments in health, education, and infrastructure—critical components of a thriving economy.

Interestingly, some indicators like **energy use per capita** and **population density** were highly correlated with GDP but had to be removed to avoid redundancy in the model. This highlights the complexity of economic modeling: not all strong correlations are useful predictors.

<img width="1183" height="784" alt="image" src="https://github.com/user-attachments/assets/05a68389-9899-47cf-b806-a995c99ca849" />

<img width="784" height="384" alt="image" src="https://github.com/user-attachments/assets/f2885cae-453d-434a-aa70-5617a17ee6a0" />

<img width="784" height="384" alt="image" src="https://github.com/user-attachments/assets/c3120639-edec-40f4-b8df-2def1107eb48" />

<img width="784" height="384" alt="image" src="https://github.com/user-attachments/assets/a3c45352-625a-4c0a-9f47-02724196c751" />

<img width="782" height="384" alt="image" src="https://github.com/user-attachments/assets/728b6800-a494-4400-8670-0fb0e5fdb0ca" />

<img width="784" height="384" alt="image" src="https://github.com/user-attachments/assets/079b1784-ed0d-41ae-bd47-735f49236d9b" />

<img width="784" height="384" alt="image" src="https://github.com/user-attachments/assets/9024d85e-c250-4f98-89b0-4a528945e6de" />

<img width="953" height="584" alt="image" src="https://github.com/user-attachments/assets/680cd4a6-8ed0-422d-a00d-641ded282540" />

---

## 💡 Creative insights from the data

One unusual insight was the role of **education parity**—the balance of school enrollment between genders—as a subtle but meaningful contributor to GDP. This suggests that inclusive education policies may have long-term economic benefits.

Another takeaway: while **energy consumption** is tightly linked to GDP, improving **energy efficiency** could maintain economic output while reducing environmental impact.

---

## 📈 How accurate is the model?

I trained three models to predict GDP:

| Model              | R² Score | RMSE (Error)       |
|--------------------|----------|--------------------|
| Linear Regression  | 0.9441   | \$44.6 billion     |
| Ridge Regression   | 0.9345   | \$48.3 billion     |
| Random Forest      | 0.8872   | \$63.3 billion     |

The **Linear Regression model** performed best, showing strong predictive power with relatively low error.

---

## 🌍 What if key indicators change?

To test the model’s predictive capabilities, I created a hypothetical scenario:

- **Population** increases by 5%
- **Energy efficiency** improves by 5%
- **Life expectancy** rises by 1 year

The model predicted a **GDP of \$4.37 trillion**, a significant jump from the actual 2024 value. This scenario illustrates how strategic improvements in health, sustainability, and demographics can drive economic growth.

<img width="784" height="484" alt="image" src="https://github.com/user-attachments/assets/f01766bd-8ffb-43f2-8c29-f84f7e5e2fd5" />


---

## 🧠 Final thoughts

This project shows how data science can uncover meaningful insights and simulate future outcomes. While models aren’t perfect, they offer a powerful lens for understanding complex systems like national economies.

Would you like to explore similar trends in other countries or test your own scenarios? The data is out there—and the possibilities are endless.

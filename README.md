
## Data Science Kya Hai?

Data Science ek aisi field hai jismein aap ko:

- Thora **math ka knowledge** (statistics)  
- Thora **computer ka kaam** (programming)  
- Aur jis **area mein aap kaam kar rahe hain**, uske bare mein knowledge hona chahiye  

Yeh sab milke **Data Science** banti hai.

---

## Data Science vs Machine Learning vs Deep Learning

Log aksar confuse hote hain ke **Data Science**, **Machine Learning**, aur **Deep Learning** aik jaisi cheezein hain.  
Lekin yeh **alag alag** hain:

- **Machine Learning** ka kaam hota hai sirf aise model bananay jo data se kuch seekh saken.  
- Lekin **Data Science** ka kaam zyada bara hota hai — yeh real duniya ke problems solve karti hai, **shuru se le kar end tak**.

# Data Science Ka Process

Data Science ka process kuch is tarah hota hai:

1. **Masla samajhna** — Pehle yeh sochte hain ke problem kya hai aur humein kya result chahiye  
2. **Data ikatha karna** — Yeh dekhna ke data kahan se milega  
3. **Data saaf karna aur samajhna** — Jo data mila usse theek tarah tayyar karna  
4. **Model banana** — Koi formula ya system tayyar karna jo data ko samjhe  
5. **Result dikhana** — Apne kaam ka result simple logon ko samjhana  
6. **Communication aur Visualization** — Asaan visuals (graphs, charts) se explain karna ke kya seekha  

> Aam log jo technical nahi hote, jaise CEO ya manager, unko samjhana hota hai ke data kya keh raha hai.  
> Iske liye **graphs**, **charts**, aur **asaan zubaan** ka use hota hai.

---

## Data Science Seekhne Ke Liye Kya Cheezein Zaroori Hain?

1. Thora **math ka ilm** (Statistics)  
2. **Machine Learning** ka basic idea  
3. Computer language jaise **Python** ka basic use  
4. **Graphs aur charts** bananay ka tareeqa  
5. Aur sabse important: **apni baat samjhana aana chahiye** — taake apna analysis managers ko asaani se samjha sako

---

**Umeed hai ab aapko ek basic idea mil gaya hoga ke Data Science kya hoti hai aur ismein kya kya seekhna hota hai.**

# Overview of Data Science Process

---

##  Data Science Kya Hai?

Data Science ek aisi field hai jisme hum **data ka istemal karke masail ka hal nikalte hain**.

Isme kuch important cheezein hoti hain jaise:

- Thora **math ka ilm** (jaise numbers ka average lena)  
- Thora **computer ka kaam** (jaise coding)  
- Thora **domain knowledge** (jaise health, shopping, ya property)

---

##  Data Science Ka Kaam Kis Tarah Hota Hai?

Yeh kaam kuch **important stages** mein hota hai. Har step ka apna maqsad hota hai. Neeche unka asaan tareeqa se zikr hai:

---

### 1.  Maslay Ko Samajhna (Problem Formulation)

Sabse pehle yeh sochte hain ke:

- Masla kya hai?  
- Kya cheez pata karni hai?  
- Kaun se data ki zarurat hai?  
- Kya result chahiye?

**Example:**  
Agar hum **ghar ki price ka andaza** lagana chahtay hain to:

- **Input:** Bedrooms, area, location  
- **Output:** Estimated price

---

### 2.  Data Ikatha Karna (Data Acquisition)

Jab masla samajh ajaye, to phir **data dhoondhna** hota hai.

Data mil sakta hai:

- Online websites (e.g., Kaggle)  
- University ya government sites  
- Apni company ke records

---

### 3.  Data Tayyar Karna (Data Preparation)

Is stage mein 2 kaam hote hain:

#### a) Data ko Samajhna (EDA - Exploratory Data Analysis)

- Data kis type ka hai?  
- Numbers theek hain ya galat?  
- Kuch values missing to nahi?

#### b) Data Saaf Karna (Preprocessing)

- Galtiyan theek karna  
- Missing values ko fill karna  
- Zarurat ho to scaling karna (e.g., 0 se 1 ke darmiyan lana)

---

### 4.  Data Ka Analysis Karna (Data Analysis & Modeling)

Ab hum **models banate hain** jo data ko samajh kar results nikalte hain:

- Sahi tareeqa chunna (e.g., regression for price prediction)  
- Algorithms se model banana (e.g., linear regression, tree-based models)  
- Best model select karna  
- **Deployment:** Model ko app ya website mein istemal karne laayak banana

---

### 5.  Natijay Samjhana aur Dikhana (Communication & Visualization)

Model ke baad natija **non-technical logon** ko dikhana hota hai (e.g., CEO, manager).

Iske liye hum use karte hain:

- **Graphs:** Bar chart, pie chart, scatter plot, etc.  
- **Visuals:** Jo result ko asaan banaye samajhne ke liye  

**Tools:**

- Python libraries (e.g., Matplotlib, Seaborn)  
- Power BI, Tableau  

**Most important skill:** Achi **communication** — taake log aapki baat asaani se samajh saken.

---

##  Aakhri Baat

**Data Science aik complete process hai** jo:

- Maslay ko samajhne se le kar  
- Result dikhane tak le jaata hai

Har step important hai:

1. Masla samajhna  
2. Data lana  
3. Data ko saaf karna  
4. Model banana  
5. Result asaani se samjhana

---

Jab aap yeh sab achi tarah seekh lein to aap **kisi bhi mushkil maslay ko data ki madad se solve kar sakte hain**.


#  Lecture 2: Understanding Types of Attributes (Data)

---

##  Data Object aur Uske Features

Data Science mein hum aise data ke sath kaam karte hain jo **table ki shakal** mein hota hai:

- **Rows (Satrain):** Har row ek shakhs, cheez ya record ko dikhati hai  
- **Columns (Ustoon):** Har column us shakhs ya cheez ke kisi aik pehlu (feature) ko dikhata hai  

**Example:**  
Agar logon ka data ho to:

- Har row = ek banda  
- Har column = jaise height, weight, job, hair color waghera

---

##  Attributes (Data ke Types)

Data ke features alag alag qisam ke ho sakte hain:

---

###  Nominal Attributes (Naam Wale)

- Sirf naam ya label hotay hain  
- Example: Hair Color → Black, Brown, Red  
- Koi order nahi hota  
- In pe math ke formulas (add, subtract) apply nahi hote  

---

###  Binary Attributes (2 Options Wale)

- Sirf do options hotay hain  
- Example: Male/Female, Smoker/Non-Smoker  
- Coding mein aksar 0 aur 1 use hotay hain  
- Kabhi dono values important hoti hain (e.g., gender)  
- Kabhi ek value zyada important hoti hai (e.g., COVID positive)

---

##  Data Ka Tayyari Ka Amal (Data Preparation)

Data analysis shuru karne se pehle 2 kaam zaroori hain:

---

###  1. Data Samajhna (EDA - Exploratory Data Analysis)

- Data kis type ka hai?  
- Missing values hain?  
- Koi value ajeeb to nahi lag rahi?  
- Columns ka aapas mein link hai?

---

###  2. Data Saaf Karna (Cleaning)

- Galat/missing data theek karna  
- Values ko standard form mein lana  
- Data ko model ke liye tayyar banana

---

##  Attributes ko Samajhna

Data ke **columns = attributes/features/variables** — ye teenon lafz aik hi cheez ke liye use hote hain.

**Example:**

- Naam: Ahmed  
- Height: 5'9"  
- Weight: 150  
- Hair Color: Brown  

Yeh sab us shakhs ke attributes hain. Puri row milke **data object** kehlati hai.

---

##  Aakhri Baat (Final Thoughts)

Data Science mein kaam karne ke liye zaroori hai:

- Data ka structure samajhna  
- Har attribute ka matlab samajhna  
- Data ko saaf karna  
- Analysis/model ke liye use karna  

Chahe attributes **nominal** hoon ya **binary**, unka role important hota hai.  
Agar yeh steps samajh lein to kisi bhi data se useful insights nikaale ja sakte hain.

---

#  Types of Attributes

---

##  Nominal Attributes (Naam Wale Features)

**Kya hota hai?**  
Sirf naam ya label batate hain — inka koi order nahi hota

**Example:**  
- Hair color: Black, Brown, Red, White

**Khaas Baat:**  
- Inmein choti ya bari value nahi hoti  
- Add/subtract nahi kar sakte  
- Sirf frequency dekhte hain (kitne logon ke baal black hain)

---

##  Binary Attributes (2 Options Wale)

**Kya hota hai?**  
Sirf do hi values hoti hain

**Examples:**  
- Gender: Male ya Female  
- COVID: Positive ya Negative  
- Smoking: Smoker ya Non-smoker

**Khaas Baat:**  
- 2 hi choices hoti hain  
- Kabhi dono barabar important  
- Kabhi aik value zyada important hoti hai  
- Frequency count kar sakte hain

---

##  Ordinal Attributes (Order Wale)

**Kya hota hai?**  
Values ka order hota hai, lekin exact difference nahi hota

**Example:**  
- Education Level: Junior, Assistant Professor, Associate Professor, Professor

**Khaas Baat:**  
- Order hota hai (choti se badi taraf)  
- Lekin har level ka fark barabar nahi hota  
- Mode, median find kiya ja sakta hai  
- Rangon mein convert kar sakte hain (e.g., Temperature → Low, Medium, High)

---

##  Numeric Attributes (Number Wale)

**Yeh wo features hain jo numbers mein hote hain** — math ke formulas apply hote hain.

###  Interval-Scaled

**Example:** Temperature (e.g., 20°C, 30°C)

**Khaas Baat:**

- Zero ka matlab “kuch bhi nahi” nahi hota  
- Gaps barabar hote hain  
- Add/subtract meaningful hote hain

###  Ratio-Scaled

**Example:** Height, Weight, Experience

**Khaas Baat:**

- Zero ka matlab hota hai “bilkul nahi”  
- 2 meter = 1 meter se double  
- Sab math operations apply hote hain

---

##  Discrete vs Continuous Attributes

###  Discrete:

- Sirf **whole numbers** hote hain  
- Example: Number of children → 1, 2, 3…

###  Continuous:

- **Decimal values** bhi ho sakti hain  
- Example: Height → 5.6, Weight → 60.3

---

##  Final Thoughts

Data Science mein kaam karte waqt samajhna zaroori hai:

- Kis type ka data hai  
- Har type ke data ke sath kaise kaam karna hai  
- Kya math apply hoti hai?  
- Kya order hai ya sirf naam?

Jab yeh concepts clear ho jaayein to:

- Data cleaning  
- Analysis  
- Aur modeling — sab asaan ho jaata hai.

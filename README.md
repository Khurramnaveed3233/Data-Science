
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

#  Lecture 4: Understanding Statistical Description in Data Science

---

##  Statistical Description Kyun Zaroori Hoti Hai?

Jab humein yeh samajhna ho ke kisi column ya feature ke andar values kis tarah banti hain ya bikhar gayi hain, to hum **statistics** ka sahara lete hain.  

**Yeh humein batata hai:**

- Data kis shape mein hai  
- Values kis had tak phaili hui hain  
- Aam ya beech wali value kya hai  
- Kya data mein koi extra ya random cheezein (noise ya bias) hain

 **Faida:**  
Yeh sab cheezein humein **data ko samajhne**, **saaf karne**, aur **analysis** ke liye tayyar karne mein madad karti hain.

---

##  Data ke Distribution ke Types

### Symmetric Distribution

- Data dono sides (left aur right) se **barabar** hota hai  
- Beech mein ek line hoti hai jo **average value** ko dikhati hai  
- Aisa data **balanced** hota hai → "normal distribution"

---

###  Skewed Distribution

Jab data **barabar nahi hota** — ek side zyada hoti hai:

#### ➕ Positive Skew:
- Data zyada **left side** par hota hai  
- Right side slow slow kam hoti hai  
- **Example:** Aam log kam kamaate hain, lekin kuch log bohot zyada kamaate hain

#### ➖ Negative Skew:
- Data pehle slow barhta hai  
- Phir **right side par achanak gir** jaata hai  
- **Common** hota hai real life mein

---

##  Statistics ke 3 Basic Measures

---

### 1.  Central Tendency (Beech ya Aam Point)

Yeh batata hai ke data ka **center** ya aam tor par value kya hai:

- **Mean:** Sab values ka average  
- **Median:** Beech ki value  
- **Mode:** Sabse zyada aayi hui value  
- **Trimmed Mean:** Outliers hata ke average  
- **Midrange:** Min + Max value ka average

---

### 2.  Dispersion (Data Kitna Phaila Hua Hai)

Batata hai ke values average ke around **kitni door ya paas** hain:

- **Paas paas:** Data tight  
- **Door door:** Data spread out  

 **Faida:** Consistency ya variation ka andaza hota hai

---

### 3.  Similarity ya Proximity (Columns Kitne Milte Hain)

Dekha jata hai ke 2 ya zyada features aapas mein **kitne similar** hain:

- Agar 2 features bohot milte hain → aik ko hata sakte hain  
- Analysis **simple aur fast** ban jata hai

---

##  Noise aur Bias Samajhna

###  Noise (Random Galti)

- Random cheezein jo data mein asar daalti hain  
- Har dafa **different** hoti hain  
- **Predict** nahi kar sakte

**Examples:**

- Weight machine har baar alag number dikhaye  
- Quiz score background noise ki wajah se kam aaya

---

###  Bias (Hamisha Aik Taraf Ka Error)

- **Fix** aur same type ki galti har dafa  
- **Predictable error** hota hai

**Example:**  
Height machine hamesha 8 inches zyada dikha rahi ho

---

###  Noise vs Bias

| Noise                     | Bias                     |
|---------------------------|---------------------------|
| Random aur alag alag      | Fix aur same             |
| Har dafa different        | Har dafa same            |
| Predict nahi hota         | Predictable error hota hai |

---

##  Outliers Kya Hote Hain?

**Outliers** wo values hoti hain jo baaqi data se **bohot alag** hoti hain.

**Example:**  
Agar sab log 20–30 saal ke hain, lekin ek value 80 saal ho — to wo **outlier** hai.

---

##  Practical Faida of Statistical Description

Jab hum basic statistics samajh lein, to hum:

- **Noise aur bias** ko identify kar sakte hain  
- **Outliers** dhoondh sakte hain  
- Data ka **shape aur spread** samajh sakte hain  
- **Aam values** jaan sakte hain  
- **Features ke relationships** samajh sakte hain  
- **Better predictive models** bana sakte hain

---

##  Aakhri Baat

Data ko analyse karne ka **pehla qadam** hai uska **basic statistical description**:

- Beech wali value kya hai (**Central Tendency**)  
- Data kitna phaila hua hai (**Dispersion**)  
- Features aapas mein kitne related hain (**Similarity**)

 **Yeh foundation hoti hai Data Science ke aage ke topics samajhne ke liye.**

# 📚 Lecture 5: Measures of Central Tendency

---

##  Central Tendency Kya Hoti Hai?

**Central Tendency** ka matlab hai data ka wo number jo **beech mein** hota hai:

- 50% data is number se **neeche** hota hai  
- 50% data is number se **upar** hota hai  

Yeh value data ka **balance point** hoti hai.

 **Example:** Jab hum logon ki **height** ya **salary** dekhte hain, zyadatar values ek beech wale number ke ird gird hoti hain.

---

##  Central Tendency ke Common Tareeqe

1. **Mean** (Average)  
2. **Median** (Beech wala number)  
3. **Mode** (Sabse zyada baar aane wali value)  
4. **Trimmed Mean** (Outlier hata ke average)  
5. **Mid-Range** (Min + Max ka average)

---

## 1.  Mean (Average)

###  Kya Hai?
Sab values ko jod kar, total number se **divide** kar dete hain.

📊 **Example:**
- 4 log kama rahe hain 100,000  
- 1 banda kama raha hai 2,000,000  
- **Average salary:** (4 × 100,000 + 2,000,000) / 5 = 4.8 lakh  

⚠️ **Masla:**  
Outliers (bohot zyada ya kam values) mean ko **disturb** kar dete hain.

---

## 2.  Trimmed Mean

###  Kya Hai?
Extreme (bahut choti ya badi) values **hata kar** average nikaala jata hai.

 **Example:**  
Agar aik value bohot high hai (jaise 2 million), to usay hata ke baqi values ka mean liya jata hai.

 **Tip:**  
Sirf **2% data** tak hi trim karna chahiye.

---

## 3.  Median

### ✅ Kya Hai?
Sorted list ka **beech wala number** hota hai.

📊 **Examples:**
- `[2, 4, 6, 8, 10]` → **Median = 6**  
- `[2, 4, 6, 8]` → **Median = (4 + 6) / 2 = 5**

✅ **Faida:**  
Outliers ka asar nahi hota  
❌ **Nuksan:**  
Data ko **sort** karna padta hai (large datasets mein slow)

---

## 4.  Mode

###  Kya Hai?
Jo value **sabse zyada baar repeat** hoti hai.

 **Example:**
- 10 log ki height = 5'8"  
- 9 log ki height = 6'1"  
- **Modes:** 5'8" and 6'1" → **Multimodal data**

 **Faida:**  
**Non-numeric data** ke liye bhi kaam karta hai (e.g., city names, colors)

---

## 5.  Mid-Range

###  Kya Hai?
**(Minimum + Maximum) / 2**

📌 Sirf ek **jaldi andaza** lagane ke liye use hota hai  
❌ **High accuracy** ke liye nahi hota

---

##  Central Tendency Se Kya Samajh Aata Hai?

Yeh measures batate hain ke data ka **shape** kaisa hai:

| Relationship               | Distribution Type       |
|---------------------------|--------------------------|
| Mean ≈ Median ≈ Mode       | Symmetric (Balanced)     |
| Mode < Median < Mean       | Positive Skew (Right)    |
| Mean < Median < Mode       | Negative Skew (Left)     |

 **Example:**
Agar aap ke paas **10,000 rows** ka data hai aur graph banana mushkil hai, to:
- **Mean, Median, Mode** nikaal lo
- Compare karo → **data skewed hai ya balanced**

---

##  Final Baat

**Central Tendency** data science ka **pehla aur basic qadam** hai:

# Lecture 6: Measure of Dispersion

## Dispersion ka matlab kya hota hai?

Data analysis mein **dispersion** ka matlab hai ke data kitna faila hua ya gathha hua hai apne beech ke number ke aas paas. Is se humein yeh pata chalta hai ke:

- Data consistent hai ya nahi  
- Sab values ek jaisi hain ya alag alag  
- Decision lena aur prediction karna kitna asaan hoga  

Agar aapko data ka spread samajh aa jaye to aap zyada ba-himmat aur sahi faislay le sakte hain.

---

## Basic Concepts: Central Tendency aur Dispersion

- **Central Tendency**: Data ka beech ka number — jaise *mean*, *median*, ya *mode*  
- **Dispersion**: Data us beech ke number ke aas paas kitna faila hua hai

---

## Quartiles aur IQR kya hote hain?

- **Quartiles**: Data ko 4 barabar hisson mein divide karne wale points
  - **Q1**: 25% data is se neeche hota hai  
  - **Q2**: 50% data ka beech (*median*)  
  - **Q3**: 75% data is se neeche hota hai  

- **IQR (Interquartile Range)**:  
  `IQR = Q3 - Q1` → beech ke 50% data ka spread  
  - Chhota IQR → data gathha hua hai  
  - Bara IQR → data faila hua hai  

---

## 5-Number Summary

Yeh 5 numbers data ka full snapshot dete hain:

1. Minimum value (sabse chhoti value)  
2. Q1  
3. Median (Q2)  
4. Q3  
5. Maximum value (sabse badi value)

---

## Data Symmetry aur Skewness

- **Symmetric Data**:  
  Q1, Q2, Q3 ka distance barabar hota hai  
- **Skewed Data**:  
  Agar left ya right side zyada faili hui ho  

---

## Box and Whisker Plot kya hai?

Yeh aik visual graph hota hai jo upar wale 5-number summary ko dikhata hai:

- **Box** → Q1 se Q3 tak ka data (IQR)  
- **Line in box** → Median  
- **Whiskers** → Box ke bahar ka range  
- **Dots** → Outliers (jo data se bohot zyada alag hain)

---

## Outliers kaise nikaalte hain?

- **Lower Bound** = `Q1 – 1.5 × IQR`  
- **Upper Bound** = `Q3 + 1.5 × IQR`  

---

## Standard Deviation aur Variance kya hoti hai?

Yeh dono cheezein tab use hoti hain jab **mean** ko central value maana jaye:

- **Standard Deviation (SD)**:  
  Batata hai ke har value mean se kitni door hai  
  - Jitni badi SD, utna zyada spread  

- **Variance**:  
  Har value ka mean se difference square karke average nikaalte hain  

---

## Kab kaunsa use karein?

| Situation            | Tool                         |
|----------------------|------------------------------|
| Median center ho     | Quartiles, IQR, Box Plot     |
| Mean center ho       | Standard Deviation, Variance |

---

## Practical Example

Aap ke paas games ki yearly sales ka data hai:

- **IQR** batayega ke beech ke 50% games ka sales kitna vary karta hai  
- **Box Plot** dikhayega koi extreme value (outlier) hai ya nahi  
- Agar koi game bohot zyada bika ho, to **outlier** hoga  

---

## Real Life Mein:

Outliers nikaal kar aap marketing ya quality problems samajh sakte ho.

---

## Final Baat

**Dispersion** aapko yeh samajhne mein madad karta hai:

- Data gathha hua hai ya spread hai  
- Outliers kahan hain  
- Data symmetric hai ya nahi  
- Kis tarah ka model ya tool use karna chahiye  


Is se aap:

- Beech wali value samajh sakte ho  
- Data ka **shape aur balance** dekh sakte ho  
- **Preprocessing** (data ko tayar karna) asaani se kar sakte ho

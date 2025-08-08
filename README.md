
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

 **Example:**
- 4 log kama rahe hain 100,000  
- 1 banda kama raha hai 2,000,000  
- **Average salary:** (4 × 100,000 + 2,000,000) / 5 = 4.8 lakh  

 **Masla:**  
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

# Lecture 7: Introduction to Proximity & Similarity

## Proximity ya Similarity Measures kya hotay hain?

Data Science mein jab hum kisi dataset ke do features ya attributes ke darmiyan taluk ya similarity samajhna chahtay hain, to hum **proximity** ya **similarity measures** use kartay hain.

Yeh measures humein yeh batatay hain:

- Do cheezain kitni milti julti hain  
- Kya unka direction ya trend ek jaisa hai  
- Kya wo dono sath barhti ya kam hoti hain  

---

## 1. Dot Product

### Kya hota hai?

Dot product aik **mathematical** tareeqa hai jo batata hai ke do vectors (features) ka **direction** kitna same hai.

### Simple Example:

Do log aik gari ko dhakka day rahay hain:

- Aik agay se aur aik peechay se → koi move nahi → dot product = `0`  
- Dono aik hi side se dhakka den to gari chalti hai → dot product **positive**

### Downside:

- Dot product **magnitude** pe depend karta hai.  
- Agar values ka size ya unit change ho jaye to result bhi change ho jata hai.

---

## 2. Cosine Similarity

### Kya hota hai?

Cosine similarity direction ko measure karta hai **baghair magnitude ke**.  
Sirf yeh dekhta hai ke direction match karta hai ya nahi.

### Range:

- `1` → Bilkul same direction  
- `0` → Bilkul different (orthogonal)  
- `-1` → Opposite direction  

### Example:

Temperature aur ice cream ki sales — dono barhtay hain sath sath → similarity high (close to `1`)

### Downside:

- Yeh sirf **direction** batata hai, lekin **taalluq ki taqat (strength)** nahi batata.

---

## 3. Covariance

### Kya hota hai?

Covariance dekhta hai ke do variables **ek sath barhtay ya ghat’tay** hain ya nahi.

- Dono sath barhtay hain → **Positive covariance**  
- Aik barhta aur doosra ghat’ta hai → **Negative covariance**

### Example:

Temperature barhne se ice cream sales bhi barhti hain → covariance **positive**

### Downside:

- Sirf **direction** batata hai, lekin **relation ki taqat** nahi.

---

## 4. Correlation

### Kya hota hai?

**Correlation** covariance ka upgraded version hai jo direction ke sath sath **strength** bhi batata hai.

### Range:

- `1` → Perfect positive relation  
- `0` → Koi relation nahi  
- `-1` → Perfect negative relation  

### Use Cases:

- Features ka taluk samajhne ke liye  
- Feature selection aur dimensionality reduction mein  

### Example:

Agar temperature barhne par sales **consistently** barhti hain → strong **positive correlation**

---

## Final Baat

In measures ko samajhna bohot zaroori hai data science mein:

- Aap samajh sakte hain ke kaunsi cheez kis cheez se kitni related hai  
- Data ko better analyze aur clean kar sakte hain  
- Model training mein better decisions le sakte hain  

 **Sabse best aur commonly used measure: Correlation**  
→ Kyun ke yeh direction bhi batata hai **aur** taqat bhi.

#  Lecture 8: Data Quality and Data Preprocessing

---

## 1 Data Quality kya hoti hai?

**Data Quality** ka matlab hai ke aapke paas jo data hai wo:

 **Sahi** ho  
 **Clean** ho  
 **Reliable** ho  

🌟 Taake uspe Machine Learning model train ho sake jo **accurate predictions** de.

###  Achi Data Quality ki Khasoosiyat:

- **Accuracy**: Ghalat values na ho (e.g., Age = 604 ❌)
- **Consistency**: Confusing ya conflicting values na ho
- **No Duplicates**: Ek hi record bar bar na ho
- **Completeness**: Missing values kam hon
- **Timeliness**: Data outdated na ho (e.g., address 10 saal purana ❌)

---

## 2 Real Life mein Data ke Maslay

Real-world data often has:

- ❗ **Missing values** (blanks in columns)
- 🔁 **Duplicate records** (ek hi person multiple times)
- ❌ **Wrong values** (Age = 800, Weight = -50)
- 🚫 **Irrelevant features** (jo analysis mein kaam nahi aate)

💡 **Garbage In = Garbage Out**  
Agar data kharab hoga → model bhi bekaar result dega.

---

## 3 Data Preprocessing – Data ko Behtar Banana

**Preprocessing** ka matlab hai data ko model ke laayak banana.

### Key Steps:

###  A. Data Cleaning:

- Duplicate records hatao  
- Fazool/irrelevant columns hatao  
- Missing data ko fill ya remove karo  

###  B. Data Integration:

- Different sources ka data combine karo  
- e.g., Lab results + DNA report + Patient info → ek table  

###  C. Data Reduction:

- Repeating ya useless features hatao  
- PCA jese techniques use karo taake kam columns mein zyada info ho  

###  D. Data Transformation:

- Features ko same **scale** par lao  
- Example:
    - Age: 1–100  
    - Income: 1 lakh – 5 crore  
    → Normalize to 0–1 scale (using Min-Max or Z-score)

 **Normalization** prevents large numbers from biasing the model.

---

## 4 Preprocessing aik dafa ka kaam nahi

Yeh **iterative process** hai — baar baar karni padti hai:

- Kabhi cleaning dobara karni parti hai  
- Kabhi transformation ke baad feature reduction zaroori hoti hai  
- Har step revise hota hai jab tak data perfect na ho

---

## 5️⃣ Akhri Baat (Final Thoughts)

Agar data quality achi ho to:

 Model accurate hoga  
 Predictions reliable hongi  
 Business problems ka behtar solution milega  

###  Important Preprocessing Steps:

- **Cleaning**
- **Integration**
- **Reduction**
- **Transformation**

 Agar data ghalat hoga → model bhi ghalat seekhega.

---

 **Lesson Summary:**
Data preprocessing is the **foundation** of successful data science and machine learning.

#  Lecture 9: Data Cleaning

---

##  Recap of Previous Lecture (Preprocessing Steps):

1. **Data Cleaning** – Data ko saaf aur sahi banana  
2. **Data Integration** – Alag sources ka data combine karna  
3. **Data Reduction** – Extra ya irrelevant features ko kam karna  
4. **Data Transformation** – Data ko readable aur model-friendly banana

👎 Poor data quality → Poor model performance  
👍 Good data quality → Better predictions

---

## 🧹 What is Data Cleaning?

Data Cleaning mein aap **detective** ki tarah kaam karte ho:

### 🔍 Detect Problems:

- Kahan values **missing** hain?
- Kya koi values **incorrect** ya **confusing** hain?
- Kya koi **row/column** purana ya **useless** hai?

---

##  Example: Gym Membership Data

Columns:

- Member ID
- Age
- Weight
- Profession
- Address
- Favourite Machine
- Join Date
- City, etc.

---

## Types of Missing Data Scenarios:

###  Scenario 1: **Row-wise Missing Data**

Aisi rows jahan 90% data missing ho (sirf ID ya naam ho):

 **Action**: Delete kar do (agar 5–10% total rows hain)

---

###  Scenario 2: **Column-wise Missing Data**

Agar kisi column (e.g., "Favourite Machine") mein 90–95% values missing hain:

 **Action**: Useless column → **Drop kar do**

---

###  Scenario 3: **Partially Missing Data**

Agar kisi column mein sirf 5–10% values missing hain:

### ✏ **How to Fill Missing Values?**

####  Method 1: Fill with **Constant value**

- Numeric column: -1
- Categorical column: "None"

 Downside: Model galat pattern seekh sakta hai

####  Method 2: Fill with **Mean / Median / Mode**

- **Mean**: If data is symmetric
- **Median**: If data is skewed
- **Mode**: For categorical data

 Example:  
Agar kisi ka weight missing hai → sab ka average weight usko assign kar do

#### 🔸 Method 3: **Group-wise Imputation**

Agar labeled data hai (e.g., Regular vs Irregular):

➡ Regular members ka average → regular member ke missing value mein  
➡ Irregular members ka average → irregular member ke liye

---

##  Summary: Data Cleaning Tips

| Situation                       | Action                     |
|--------------------------------|----------------------------|
| Row with 90% missing data      | Delete                    |
| Column with 90–95% missing     | Delete                    |
| Few missing values             | Fill with:                |
|                                | - Constant (e.g., -1, "None") |
|                                | - Mean / Median / Mode     |
|                                | - Group-wise average       |

 Har dataset different hota hai → **Experimentation is important**

---

# Lecture 10: Resolving Inconsistent Values

Pehla masla humne solve kiya tha — missing values ka. Lekin doosra masla bhi tha — inconsistency.  
Iska matlab hota hai ke data ek jaisa nahi likha gaya. Jaise gym ke data mein "City of Birth" ke andar  
Lahore likhne ke kai tareeqe hain. Kahin capital letters mein LAHORE, kahin LHR, kahin small letters  
mein lahore. Ye sab ek hi cheez hain lekin tareeqa alag alag hai — isay kehte hain inconsistent data.  

Agar hum aise data ko model mein daalenge, to system har version ko alag cheez samjhega — jisse asli  
insight khatam ho jaayegi. Iska solution hai standardization — yani decide karna ke hum Lahore ko  
sirf "lahore" (small letters mein aur poori spelling ke saath) likhenge.  

Iske liye ek chhoti si script likh lete hain jo har jagah jo bhi variation ho (jaise LHR, lahore, LAHORE),  
sabko "lahore" mein badal deta hai. Isi tarah Karachi ya Faisalabad ke saath bhi karte hain.  

Dusra tareeqa hota hai validation — jisme hum dekhte hain ke ek record ke do values aapas mein  
match karti hain ya nahi.  

Jaise ek member ki Date of Birth se calculate ki gayi age 30 saal banti hai, lekin record mein likha hua  
hai 45 saal. Yani mismatch hai. Phir hum decide karte hain ke hum kis value ko trust karenge —  
calculated age ya written age? Ye decide karne ke baad hum data ko clean kar lete hain.  

Agla masla hota hai duplicate data ka — yani ek hi banda ka data system mein 2 dafa aa gaya. Ye  
kabhi kabhi hota hai jab form 2 dafa submit ho jaye ya kisi wajah se system mein ek hi cheez 2 dafa  
store ho jaaye.  

Agar humne member ID unke CNIC pe banayi ho to duplicate pakarna easy hota hai — kyunke CNIC  
duplicate nahi hota. Lekin agar humne apne tareeqe se random ID di ho jaise "CYS13" waghera, to phir  
humein dekhna padega:  

- Kya name same hai?  
- Kya age, weight, aur dusri cheezen match karti hain?  

Agar sab cheezen match karti hain to shayad wo duplicate ho sakta hai. Nahi to nahi.  

Uske baad aata hai noisy ya inaccurate data — yani galat ya bekar data. Jaise kisi bande ki age likhi ho  
270 saal ya 573 saal — jo clearly possible nahi.  

Aise data ko outlier kehte hain. Hum decide karte hain ke gym ka member 18 se 60 saal ke darmiyan  
hoga. Is range ke bahar koi bhi age ho to hum usay galat ya suspicious maanenge.  

Aise outliers ko ya to delete karte hain, ya unko "missing value" bana ke fill karne ki techniques lagate  
hain jaise humne missing data ke case mein kiya tha.  

Aakhri aur important masla hota hai stale data — yani purana data jo update nahi hua. Jaise kisi  
member ka address 10 saal pehle ka ho. Agar hum us address pe email ya brochure bhejenge to shayad  
wo banda wahan na ho.  

To hum check karte hain ke last updated kab hua tha? Agar 2 saal se zyada guzr chuke hain to samajh  
jaate hain ke wo data purana hai. Hum sirf un logon ko contact karte hain jinka data recent hai.  

---

To dosto, is puri discussion mein humne yeh seekha:  

- Missing values kaise handle karte hain  
- Inconsistent data ko kaise standardize karte hain  
- Duplicate records kaise identify karte hain  
- Noisy ya outlier data ko kaise clean karte hain  
- Stale data kaise detect aur manage karte hain  

Ye sab cheezein milke data ko accurate, saaf aur useful banaati hain — jisse hum real world problems  
ko solve kar sakte hain.  

# Skewness Kya Hoti Hai?
Skewness ka matlab hai ke data ka shape barabar nahi hota – yani ke left aur right side ek jaise nahi lagtay (mirror image nahi hotay).

### Teen Qisam ki Skewness Hoti Hai:
1. **Right Skewed (Positive Skew)** – Jab graph ka right side (daiin taraf) lamba hota hai.
2. **Left Skewed (Negative Skew)** – Jab graph ka left side (baen taraf) lamba hota hai.
3. **Zero Skewness** – Jab graph ka shape bilkul barabar ho, left aur right side dono same hoon.

<img width="1428" height="386" alt="Skewness-of-a-distribution" src="https://github.com/user-attachments/assets/6d893f49-1c0b-49d7-8774-bc246a6917fa" />

---

## 1. Zero Skew
Jab data symmetrical ho – yaani left aur right side ek jaise hoon – to isay zero skew kehte hain.

<img width="1276" height="962" alt="Zero-skew-symmetrical" src="https://github.com/user-attachments/assets/aba8008c-409f-45c2-9205-92f8d17300a1" />


## Graph mein kya dikhaya gaya hai?

**Middle graph** (Zero Skew) mein:

- **X-axis**: Chick ka **weight** (wazan) hai  
- **Y-axis**: **Frequency** hai — yaani kitne chicks ka woh wazan hai

---

## Samajhne ka Asaan Tareeqa:

Socho tumhare paas **100 chicks** hain, aur tum unka wazan measure kar rahe ho. Jab tum data ka graph banate ho to:

- Zyada tar chicks ka wazan **beech mein hota hai** (e.g., 250–270 grams)
- Kuch chicks ka wazan **thoda kam** hota hai (e.g., 230 grams)
- Kuch chicks ka wazan **thoda zyada** hota hai (e.g., 290 grams)
- Lekin dono sides (kam aur zyada wazan) **barabar** hain

---

## Iska Matlab:

- Graph ka **center mein ek peak** hai (most chicks ka weight)
- Left aur right **barabar taper ho rahe hain**
- Koi lambi tail nahi hai kisi ek side pe
- **Mean ≈ Median** (average aur beech wala number lagbhag same)

---

## Bottom Line (Layman Ki Zuban Mein):

**Zero skewness ka matlab hai ke zyada tar chicks ka weight average ke aas paas hai.**

- Kuch ka thoda kam
- Kuch ka thoda zyada
- **Lekin dono taraf ka data balance hai**

Graph dono sides se ek jaisa dikhta hai, jaise **mirror image**.

Yani data **bilkul theek balance** mein hai –  
**na left ko jhukta hai, na right ko.**

### Asaan alfaaz mein:
- Jab distribution ka shape dono taraf barabar ho, to skew zero hoti hai.
- Normal distribution (bell shape) zero skew hoti hai.
- Uniform ya bimodal distributions bhi zero skew ho sakti hain.

### Kaise pata chale?
Histogram banao – agar shape dono taraf se same lage to skew zero hai.

**Example**: Agar chicks ka average weight 261.3g aur median 258g hai, to ye qareeb qareeb same hain → skew almost zero.

> Real-life data mein halki-phulki skewness normal hoti hai. Agar shape mostly barabar ho to practically usay zero skew samjha jata hai.

**Bottom Line**: Jab mean ≈ median ho to data almost zero skew hota hai.

---

## 2. Right Skew (Positive Skew)
Right-skewed ka matlab hota hai ke graph ka right side lamba ho. Yani kuch bohat zyada values hoti hain jo rarely aati hain.

<img width="1277" height="962" alt="Right-skew-Positive-skew" src="https://github.com/user-attachments/assets/56247355-e9ec-48d4-bc9d-89eda4d5e4ba" />

Dekho, graph mein **left side (0–50)** par bohot saara data ikattha hai — bars unchi hain.  
Phir jaise-jaise **right side (100–200)** ki taraf jaate ho, bars chhoti hoti ja rahi hain, matlab wahan data kam hai.  

**Tail ka matlab**: Graph ka woh patla lamba hissa jahan thoda sa data hota hai.  
Yahan wo patla hissa **right side** par hai, is liye isay **right-skewed** kehte hain.  

 **Easy yaad rakhne ka tareeqa**:  
> "Jis side tail hoti hai, us side ka naam lagta hai."  
> Yahan tail right me → **Right-skewed**.

### Right-Skewed Graph Ko Simple Tarike Se Samajhna

1. **Zyada data kahan hai?**  
   Graph ki **left side (0–50)** par bars unchi hain → iska matlab wahan data zyada hai.

2. **Kam data kahan hai?**  
   Jaise-jaise **right side (100–200)** ki taraf jaate ho, bars chhoti hoti ja rahi hain → matlab wahan data kam hai.

3. **Tail ka matlab**  
   Tail woh patla aur lamba hissa hota hai jahan data bohot kam hota hai.  
   Yahan tail **right side** par hai.

4. **Naam ka rule**  
   > "Jis side tail hoti hai, us side ka naam lagta hai."  
   Yahan tail right me hai → **Right-skewed**.

##  Graph mein kya dikhaya gaya hai?

- **X-axis**: Har saal mein **Sunspots ki tadaad** (Number of sunspots per year)
- **Y-axis**: **Frequency** (Yaani kitne saal mein woh sunspot count aaya)

---

## ☀Samajhne ka Asaan Tareeqa:

Socho ke scientists har saal **sun ke upar dark spots** count karte hain (sunspots). Jab unhone 1749 se 1983 tak data collect kiya aur graph banaya, to:

- **Zyada saal** aise thay jahan sunspots **kam the (0–60)**  
- **Kuch saal** aise thay jahan sunspots **bahut zyada ho gaye (100+), lekin woh saal rare thay**

---

## Kya Dikh Raha Hai?

- Graph ka **peak left side** pe hai (wahan data zyada hai)
- **Right side pe ek lambi tail** hai (wahan kuch hi values hain lekin woh bohat zyada hain)
- Iska matlab: **Zyada sunspots wali values rare hain**, lekin jab hoti hain to bohat high hoti hain
- **Mean (average)** → right side chala jata hai  
- **Median (middle value)** → mean se pehle hota hai

---

## Right Skewness Ka Rule:

**Right skew (Positive Skew)** jab hota hai jab:

### Sochne ka tareeqa:
- **Tail** ka matlab hota hai graph ka lamba patla hissa.
- Jab tail right side pe lambi ho to data right-skewed hota hai.

**Example**: Sunspots (suraj pe daag) ke yearly data ka graph right-skewed hai:
- Right side lamba hai
- Kabhi kabhi zyada sunspots hote hain, is wajah se tail lambi hai

### Mean aur Median ka Relation:
- **Right Skew Rule**: Mean > Median
- Example:
  - Mean = 48.6
  - Median = 39
  → Mean zyada hai → right skewed distribution

**Bottom Line**: Right skew ka matlab hai kuch bohat bade numbers mean ko upar kheench lete hain → shape right taraf lamba hota hai.

## 3. Left Skew (Negative Skew)

Left-skewed distribution mein graph ka left side lamba hota hai.

<img width="1276" height="962" alt="Left-skew-Negative-skew" src="https://github.com/user-attachments/assets/019204ed-555d-4c4a-b1cf-2aa79ffb802b" />


1. **Zyada data kahan hai?**  
   Graph ki **right side (55–65)** par bars unchi hain → iska matlab wahan data zyada hai.

2. **Kam data kahan hai?**  
   Jaise-jaise **left side (30–45)** ki taraf jaate ho, bars chhoti hoti ja rahi hain → matlab wahan data kam hai.

3. **Tail ka matlab**  
   Tail woh patla aur lamba hissa hota hai jahan data bohot kam hota hai.  
   Yahan tail **left side** par hai.

4. **Naam ka rule**  
   > "Jis side tail hoti hai, us side ka naam lagta hai."  
   Yahan tail left me hai → **Left-skewed (Negative skew)**.

5. **Extra Note – Mean aur Median ka signal**  
   Left-skewed graph me **mean** aksar **median se chhota** hota hai, jaise yahan dikh raha hai.

### Left-Skewed Graph Ko aur asani se smjhte hen 

1. **Data ka zyada hissa**  
   Graph ki **right side** (55–65) par bars unchi hain → matlab zyada logon ke marks yahan hain.

2. **Data ka kam hissa**  
   Graph ki **left side** (30–45) par bars chhoti hain → matlab kam logon ke marks yahan hain.

3. **Tail ka matlab**  
   Tail = Graph ka lamba patla hissa jahan data bohot kam hota hai.  
   Yahan tail **left side** par hai.

4. **Naam ka rule**  
   > "Jis side tail hoti hai, usi side ka naam hota hai."  
   Tail left me → **Left-skewed**.

5. **Extra hint**  
   Left-skew me **mean** (average) hamesha **median** se thoda pehle hota hai.

###  Graph Mein Kya Dikh Raha Hai?

- Ye graph students ke **zoology test scores** ko dikhata hai.
- Zyada students ne **50 se 65 ke darmiyan** marks liye hain.
- Kuch students ne **bohot kam marks** liye (jaise 30–40 ke darmiyan).

---

###  Left Skewness Kya Hoti Hai?

- Jab **zyada log ache marks lein**, lekin **kuch log bohot kam marks lein**,  
  to graph ka **tail ya lambi line left side** (kam marks) ki taraf chali jati hai.
- Isko **left skewed** ya **negative skewed** kehte hain.

---

###  Mean aur Median Ka Farq:

- **Mean** = sab scores ka average  
- **Median** = beech wala score

**Left skewed distribution mein:**
- **Mean (average)** neeche chala jata hai (kam ho jata hai),
- **Median** us se zyada hota hai.

_Is image mein bhi yehi ho raha hai:_
- **Mean** left side pe hai
- **Median** thoda right side pe hai

---

###  Ek Asaan Example:

Sochiye 10 students ne test diya:

30, 35, 50, 55, 56, 58, 59, 60, 62, 64


- Zyada students ne **55–65** ke darmiyan score kiya.
- Sirf 2 students ne **bohot kam** score kiya (30, 35)
- Is wajah se **average (mean) neeche** chala gaya

➡ **Yahi hoti hai left skewness**

---

###  Summary

- **Tail** (graph ki lambi line) **left** side pe hoti hai.
- **Mean < Median**
- Aise distribution ko **left skewed** ya **negative skewed** kehte hain.

### Matlab:
- Zyada logon ke numbers achay hote hain
- Sirf kuch log hote hain jin ke marks ya values bohat kam hoti hain
- Wo chhoti values left side pe tail bana deti hain

**Example**: Zoology test scores ka histogram:
- Zyada students ke achay marks hain
- Sirf kuch students ne bohat kam marks liye
- Graph ka left side lamba hai → left-skewed distribution

### Mean aur Median ka Relation:
- **Left Skew Rule**: Mean < Median
- Example:
  - Mean = 53.7
  - Median = 55
  → Mean chhota hai → left skewed distribution

**Bottom Line**: Jab kuch values bohat kam hoti hain (left tail), wo mean ko neeche le jaati hain, is liye mean < median hota hai.

---

## Summary:
| Skew Type         | Tail Direction | Mean vs Median    |
|-------------------|----------------|-------------------|
| Zero Skew         | Symmetrical    | Mean ≈ Median     |
| Right Skew        | Right Side     | Mean > Median     |
| Left Skew         | Left Side      | Mean < Median     |


---




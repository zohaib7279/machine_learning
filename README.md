# machine_learning

## Machine Learning:

Machine learning is a field of computer science that uses statistical techniques to give computer systems the ability to "learn" with data, without being explicitly programmed.

data information hota ha. data collect karke anaylize karta ha

Machine learning computer ko examples da ka osa sochne aur samajna ka qabil banata ha

jab pehla AI aya to os ma kai cheza thi jo ham nahi kar sakte tha AI ki madad sa is liya is ka liya ML ya aur use hoa

ML ma hame rule khud nahi dena parta balka vo khd generate karta ha bas ham na osa sahi data dena hota ha

AI ki complex problem solve karna ka liya ML aur ML ki complex problem solve karna ka liya DL use hota ha

## Machine Learning ki 4 types ha

1. supervised

2. unsupervised

3. semi supervised

4. Reinforment

## Machine Learning ke 4 main types:

### Supervised Machine Learning

Supervised Machine Learning mein pehle se correct answers diye jate hain, phir system un se seekhta hai aur new answers predict karta hai.

### 2. Unsupervised Learning

Is mein answers nahi hote.  
System khud pattern dhoondta hai.

Misal: Students ko groups mein divide karna.

### Semi-Supervised Learning

Is mein kuch data labelled hota hai (answers hote hain) aur kuch data unlabeled hota hai (answers nahi hote).

System pehle labelled data se seekhta hai, phir us knowledge ko use karke baqi unlabeled data ke answers predict karta hai.

Misal: Kuch students ki CGPA ho, baqi predict kare.

### 4. Reinforcement Learning

System reward aur penalty se seekhta hai.

Misal: Game khelne wala AI.

Yaad rakho:  
Galti se seekhta hai.

## Short Summary:

Supervised = Sare answers  
Unsupervised = No answers  
Semi-Supervised = Kuch answers  
Reinforcement = Reward/Penalty

rate learning is liya use hota ha ka ham poorani cheza bi yaad rakha aur nai cheza bi seekha

agar koi shaksh aik product banata ha ya bohat bari problem hoti ha agar ma na aik product banaya to ma osa agar aim saal baad check karo to poorani reh jay gi cheza hama roz ki roz os ki update vgra upgrade karni chiya ha

offline ml = batch

jab ham batch karta ha to data ko seedha hi train karta ha magara jab ham online machine learning krta ha to hama ona group ma divide karn aprta ha

river aur vowpal wabit aik library ha

## 1. Memorizing

Sirf cheezein yaad karna

Example:  
Agar student answers ratta laga le

online ml ka Disvantages bi ha jis ma risky aur trisky use ha

risky ya hota ha ka agara ham na model banaya to agar ham na apna model ka behavior change Karna h to koi Hama hack kar skate ha is vja sa Hama server sa osa otarna para ta ha

## 2. Generalizing

Nayi situation me bhi sahi answer dena

Machine Learning me ye zyada important hai

```text
          learning
         /        \
   memorizing   generalizing
```

istance based learning aur model based learning

dono hi ml ka algorithms sa find karta ha jasa ka instance machine learning kai assan hota ha ab hamara pas student ka data ha jis ma iq cgpa aur placement ha ab jo placement ha vo yes aur no ka field ki ha ab ham instance learning is liya use karta ha take ham identify kar ske istance based learing ma similarity hoi ha sari model nahi hota is logic ko knn kehta ha algrithim asa hi batha rehta ha jab new query points ay to vo phir new query points sa jis ka placement nahi hoa os ka Karta ha ml algorithm is ma aik vacate ma aik hi

model based learning ko two query points milta ha agar os ki do aik boundry hoti ha boundry yan border sa bahir jo hota ha jab bahir new query points ata ha to vo osa border ka bahir jo students ha os ka placement ko yes aur jab boundy ka andar query points aye ga to osa no define kar de ga ml algorithem

sari example model based learning ki hoti ha bas thori hi instance based learning k hoti ha

# Differences Between Model Based Learning And Instance Based Learning

## 1. Training

**Model Based Learning:**  
Model ko train kiya jata hai aur patterns discover kiye jate hain.

**Instance Based Learning:**  
Model train nahi hota. Prediction ke waqt direct data use hota hai.

## 2. Model Storage

**Model Based Learning:**  
Model ko save/store kiya jata hai.

**Instance Based Learning:**  
Koi proper model store nahi hota.

## 3. Generalization

**Model Based Learning:**  
Prediction se pehle hi rules generalize kar leta hai.

**Instance Based Learning:**  
Har new instance ko alag se compare karta hai.

## 4. Prediction

**Model Based Learning:**  
Prediction trained model se hoti hai.

**Instance Based Learning:**  
Prediction training data ko direct compare karke hoti hai.

## 5. Training Data

**Model Based Learning:**  
Training ke baad original data hata sakte hain.

**Instance Based Learning:**  
Training data ko rakhna zaroori hota hai.

## 6. Storage

**Model Based Learning:**  
Kam storage use hoti hai.

**Instance Based Learning:**  
Zyada storage use hoti hai.

## 7. Speed

**Model Based Learning:**  
Prediction fast hoti hai.

**Instance Based Learning:**  
Prediction slow ho sakti hai.

## 8. Example

**Model Based Learning:**  
Linear Regression, Decision Tree

**Instance Based Learning:**  
KNN (K-Nearest Neighbors)

```text
        data collection
         /        \
       API      web scraping
```

# Machine Learning Development Life Cycle (MLDLC/MLDC)

## challenges in ml:-

- Data Collection
- Insufficient Data/Labelled Data
- Non Representative Data
- Poor Quality Data
- Irrelevant Features
- Overfitting
- Underfitting
- Software Integration
- Offline Learning/Deployment
- Cost Involved

## Application in ml:-

- Retail – Amazon / Big Bazaar
- Banking and Finance
- Transport – OLA
- Manufacturing – Tesla
- Consumer Internet – Twitter

eda input aur output ka relationship batata ha

Vizs

- Univariate / Bivariate
- Outlier detection
- Importance →

ham apna model ko backup sa data sa remote control sa aur bi kuch chezo sa server control rehta ha

testing li commonly use testing a/b testing ha ya karna ka baaad yani a/b testing karna ka baad optimize karta ha

pehla hamara pas aik model hota ah phir vo binary file ka pass jata ha aur vaha sa aik api ban kar niklta ha in sabka baad os ka beta testing karna ha

data Enginier vo hota ha jo user ko data lakar table ma deta ha

oltp - olapf

jab hamara pas data a jata ha to phir os data ko create analysist karta ha aur vo logo ko sikhata aur log aga sa naye model banata ha

## data sciencetist:

“A data scientist is someone who is better at statistics than any software engineer and better at software engineering than any statistician.”

ya vo banda jis ko sab kuch ata ha jo complete work through ha

data scientist aur data anlisist ma sab sa Zada bara yahi fraq ha ka data analisysis past ko aur data scientist futer ka bary ma sochta ha

data scienctest ko fullstack bi kehta ha

## ml enginer:

jab model ban jata ha to os ka bohat chota sa kaam hota ha ka os model ko deploy kar yani os ki deployment karna

Sab se pehle Data Engineer data ready karta hai. Phir Data Analyst us data ko analyze karta hai. Us ke baad Data Scientist us data se model banata aur train karta hai. Jab model tayyar ho jata hai to ML Engineer us ki deployment karta hai.

| Role | Analytical Skills | Business Acumen | Data Storytelling | Soft Skills | Software Skills |
|--------|------------------|-----------------|-------------------|-------------|-----------------|
| Data Analyst | High | Medium to High | High | Medium to High | Medium |
| Data Engineer | Medium | Low | Low | Medium | High |
| Data Scientist | High | High | High | High | Medium |
| ML Engineer | Medium to High | Medium | Low | High | High |

----------------------------------------------------------------------------------------------------------

[1,2,3,4] ya aik 1d tesnor bi ha ya aik vector bi ha aur ya 1d array bi ha
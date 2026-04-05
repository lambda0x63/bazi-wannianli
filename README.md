# Manseoryeok 萬年曆

## Calculation Principles

### Four Pillars 四柱 Calculation

#### Year Pillar 年柱

* The Year Pillar changes at **立春 (Lìchūn)**.
* Birth before **立春** follows the previous year’s **干支 (gānzhī)**.
* Birth on or after **立春** follows the current year’s **干支**.
* The exact time of **立春** is based on data from the Korea Astronomy and Space Science Institute.
* Formula: **(Gregorian year - 4) % 60** = **六十甲子 (liùshí jiǎzǐ)** index. 

#### Month Pillar 月柱

* The Month Pillar is determined by the 12 **節 (jié)** among the **二十四節氣 (èrshísì jiéqì)**.
* The exact time of **節入** is applied.
* Terms used: **立春 (Lìchūn, 寅), 驚蟄 (Jīngzhé, 卯), 淸明 (Qīngmíng, 辰), 立夏 (Lìxià, 巳), 芒種 (Mángzhòng, 午), 小暑 (Xiǎoshǔ, 未), 立秋 (Lìqiū, 申), 白露 (Báilù, 酉), 寒露 (Hánlù, 戌), 立冬 (Lìdōng, 亥), 大雪 (Dàxuě, 子), 小寒 (Xiǎohán, 丑)**.
* Before **節入**, the previous month’s **干支** is used.
* After **節入**, the corresponding month’s **干支** is used. 

#### Day Pillar 日柱

* Base date: January 1, 1900 = **甲戌日 (Jiǎxū day)**.
* Calculated by taking the elapsed number of days from the base date modulo 60.
* Day change follows **00:00** midnight. 

#### Hour Pillar 時柱

* **地支 (dìzhī)** time mapping:

  * **23:00-01:00** = **子時 (Zǐ shí)**
  * **01:00-03:00** = **丑時 (Chǒu shí)**
  * **03:00-05:00** = **寅時 (Yín shí)**
  * **05:00-07:00** = **卯時 (Mǎo shí)**
  * **07:00-09:00** = **辰時 (Chén shí)**
  * **09:00-11:00** = **巳時 (Sì shí)**
  * **11:00-13:00** = **午時 (Wǔ shí)**
  * **13:00-15:00** = **未時 (Wèi shí)**
  * **15:00-17:00** = **申時 (Shēn shí)**
  * **17:00-19:00** = **酉時 (Yǒu shí)**
  * **19:00-21:00** = **戌時 (Xū shí)**
  * **21:00-23:00** = **亥時 (Hài shí)**
* **子時** is divided as follows:

  * **23:00-24:00** = **夜子時 (Yèzǐshí)** — same day
  * **00:00-01:00** = **早子時 (Zǎozǐshí)** — same day
* The Hour Stem is derived from the Day Stem and Hour Branch. 

#### Time Adjustment 時間補正

* Korean daylight saving time:

  * 1948-1960: +1 hour
  * 1987-1988: +1 hour
* **眞太陽時** and **均時差** are not applied. Legal standard time is used. 

### Major Luck 大運 Calculation

#### Starting Age of 大運

1. Determine **順行 (shùnxíng)** or **逆行 (nìxíng)**

   * **順行**: **陽干** male, **陰干** female
   * **逆行**: **陽干** female, **陰干** male

2. Calculate the interval

   * **順行**: from birth time to the next **節氣**
   * **逆行**: from birth time to the previous **節氣**

3. Conversion rule

   * 3 days = 1 year
   * 1 day = 4 months
   * 1 hour = 5 days
   * Starting age of **大運** = days divided by 3. 

#### 大運 干支 Sequence

* **順行** advances in sequence from the Month Pillar.
* **逆行** moves backward from the Month Pillar.
* Each cycle changes every 10 years. 

### Annual Luck 歲運

* Follows the **六十甲子** cycle.
* Display range: from 10 years before the current year to 10 years after.
* Age is calculated in full years.
* The current year is highlighted. 

### 神煞 and 空亡

#### 貴人 and 吉神

* **天乙貴人 (Tiānyǐ Guìrén)** based on the Day Stem
  **甲戊庚-丑未 / 乙己-子申 / 丙丁-亥酉 / 辛-寅午 / 壬癸-卯巳**
* **文昌貴人 (Wénchāng Guìrén)** based on the prosperity branch of **食神** for each Day Stem
  **甲-巳 乙-午 丙-申 丁-酉 戊-申 己-酉 庚-亥 辛-子 壬-寅 癸-卯**
* **天德 / 月德貴人 (Tiāndé / Yuèdé Guìrén)** based on the Month Branch
  **Spring-丙/丁, Summer-庚/辛, Autumn-壬/癸, Winter-甲/乙** 

#### 三合-Based 神煞

* **驛馬煞 (Yìmǎ shà)**: the branch that clashes with the first branch of the triad
  **亥卯未-巳 / 寅午戌-申 / 巳酉丑-亥 / 申子辰-寅**
* **桃花煞 (Táohuā shà)**: the bathing branch derived from the triad
  **亥卯未-子 / 寅午戌-卯 / 巳酉丑-午 / 申子辰-酉**
* **華蓋煞 (Huágài shà)**: the storage branch of the triad
  **亥卯未-未 / 寅午戌-戌 / 巳酉丑-丑 / 申子辰-辰** 

#### Main 煞

* **空亡 (Kōngwáng)**: the missing branches within the **旬 (xún)** of the Day Pillar
  **甲子旬-戌亥 / 甲戌旬-申酉 / 甲申旬-午未 / 甲午旬-辰巳 / 甲辰旬-寅卯 / 甲寅旬-子丑**
* **羊刃煞 (Yángrèn shà)**: the branch of extreme force for each Day Stem
  **甲-卯 / 乙-寅 / 丙-午 / 丁-巳 / 戊-午 / 己-巳 / 庚-酉 / 辛-申 / 壬-子 / 癸-亥**
* **魁罡煞 (Kuígāng shà)**: applies when the Day Pillar is
  **庚辰, 庚戌, 壬辰, 戊戌**
* **白虎大煞 (Báihǔ dàshà)**: applies to the following combinations
  **甲辰, 乙未, 丙戌, 丁丑, 戊辰, 壬戌, 癸丑**
* **元辰煞 / 鬼門關煞 (Yuánchén shà / Guǐménguān shà)**: specific branch pairings
  **子未, 丑午, 寅巳 / 寅未, 卯辰 / 卯申, 申亥, 酉戌 / 酉午, etc.** 

## Display Data

### 原局

* Eight Characters of the **天干地支**
* **五行 (wǔxíng)** color coding

  * 木: **#66BB6A**
  * 火: **#EF5350**
  * 土: **#FFCA28**
  * 金: **#BDBDBD**
  * 水: **#42A5F5**
* **陰陽**

  * 陽: white text
  * 陰: black text 

### 十神

* Determined by the elemental relationship to the **日主 (rìzhǔ)**:

  * **比劫 (bǐjié)**: same element

    * **比肩 (bǐjiān)** = same polarity
    * **劫財 (jiécái)** = opposite polarity
  * **食傷 (shíshāng)**: element produced by the Day Master

    * **食神 (shíshén)** = same polarity
    * **傷官 (shāngguān)** = opposite polarity
  * **財星 (cáixīng)**: element controlled by the Day Master

    * **偏財 (piāncái)** = same polarity
    * **正財 (zhèngcái)** = opposite polarity
  * **官殺 (guānshà)**: element controlling the Day Master

    * **七殺 (qīshà)** = same polarity
    * **正官 (zhèngguān)** = opposite polarity
  * **印星 (yìnxīng)**: element producing the Day Master

    * **偏印 (piānyìn)** = same polarity
    * **正印 (zhèngyìn)** = opposite polarity
* For **地支**, the **十神** are determined from the main hidden stem.
* For hidden stems, the **十神** are calculated separately for **本氣 / 中氣 / 餘氣**. 

### 地支藏干

```text id="hs01"
子 癸        丑 己癸辛     寅 甲丙戊     卯 乙
辰 戊乙癸     巳 丙庚戊     午 丁己       未 己丁乙
申 庚壬戊     酉 辛        戌 戊辛丁     亥 壬甲
```



### 天干 合沖

* **五合 (wǔhé)**
  **甲己→土, 乙庚→金, 丙辛→水, 丁壬→木, 戊癸→火**
* **沖 (chōng)**
  **甲庚沖, 乙辛沖, 丙壬沖, 丁癸沖**
* **戊己** do not form **沖**. 

### 地支 合沖

* **六合 (liùhé)**
  **子丑→土, 寅亥→木, 卯戌→火, 辰酉→金, 巳申→水, 午未→土**
* **三合 (sānhé)**
  **申子辰→水局, 亥卯未→木局, 寅午戌→火局, 巳酉丑→金局**
* **六沖 (liùchōng)**
  **子午沖, 丑未沖, 寅申沖, 卯酉沖, 辰戌沖, 巳亥沖** 

## Data Sources

* Solar term data (1946-2024, Korea Astronomy and Space Science Institute)
* Hidden stem and **神煞** rules from **淵海子平 (Yuānhǎi Zǐpíng)** and **三命通會 (Sānmìng Tōnghuì)**. 

## Environment Setup

```bash id="env01"
npm install
npx prisma db push
npm run dev
```

```env id="env02"
DATABASE_URL="postgresql://..."
NEXT_PUBLIC_SUPABASE_URL="https://..."
NEXT_PUBLIC_SUPABASE_ANON_KEY="..."
```

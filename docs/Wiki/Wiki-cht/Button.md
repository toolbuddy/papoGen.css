> 元素/按鈕

按鈕是用來觸發動作


* **前言:** `btn`
* **預設**

    | 預設 | 名 | 描述 |
    |---|---|---|
    | 按鈕 | `btn` | 標準按鈕，同預設 |

* **屬性**

    | 屬性 | 名 | 描述 |
    |---|---|---|
    | 主要 | `primary` | 主按鈕 |
    | 次要 | `secondary` | 次要按鈕 |
    | 基本 | `basic` | 有框架的基本按鈕設定 |
    | 標註 | `labeled` | 有標籤的按鈕 |
    | 群組 | `buttons` | 群組按鈕 |
    | 水平 | `horizontal` | 水平方式群組按鈕 |
    | 垂直 | `vertical` | 垂直方式群組按鈕 |
    | 上 | `up` | 底部邊角沒有弧度的按鈕 |
    | 下 | `down` | 頂端邊角沒有弧度的按鈕 |
    | 中間 | `center` | 邊角沒有弧度的按鈕 |
    | 左邊 | `left` | 右邊角沒有弧度的按鈕 |
    | 右邊 | `right` | 左邊角沒有弧度的按鈕 |
    | 小 | `small` | 較小的按鈕 |
    | 中 | `medium` | 普通大小的按鈕(為預設) |
    | 大 | `large` | 較大的按鈕 |



---
## 1. 型態

### 1.1 預設

* 預設按鈕
* **舉例**
    ```html
    <div class = "btn"></div>
    ```
* 主要按鈕
* **舉例**
    ```html
    <div class = "primary btn"></div>
    ```
* 次要按鈕
* **舉例**
    ```html
    <div class = "secondary btn"></div>
    ```

### 1.2 Basic

* 按鈕的簡易設計
* **舉例**
    ```html
    <div class = "basic btn"></div>
    ```

### 1.3 倒

* 
* **舉例**
    ```html
    ```

### 1.4 圖標

* 只有圖標的按鈕
* **舉例**
    ```html
    <div class = "basic btn">
        <i class = "icon cloud"></i>
    </div>
    ```
* 有圖標和文字的按鈕
* **舉例**
    ```html
    <div class = "basic btn">
        <i class = "left icon cloud"></i> cloud
    </div>
    <div class = "basic btn">
        cloud <i class = "right icon cloud"></i>
    </div>
    ```

### 1.5 標籤

* 按鈕左邊加標籤
* **舉例**
    ```html
    <div class = "labeled btn"> 
        <div class = "basic button">
            <i class = "left icon mail"></i> mail
        </div>
        <div class = "label">receive</div>
    </div>
    ```

### 1.6 標籤圖標

* 
* **舉例**
    ```html
    ```

### 1.7 Animated

* 
* **舉例**
    ```html
    ```

---
## 2. 群組

### 2.1 按鈕

* 按鈕可以群組化
* **舉例**
    + 水平式群組按鈕
    ```html
    <div class = "horizontal buttons">
        <div class = "basic left btn">Left</div>
        <div class = "basic center btn">Center</div>
        <div class = "basic right btn">Right</div>
    </div>
    ```
    + 垂直式群組按鈕
    ```html
    <div class = "vertical buttons">
        <div class = "basic up btn">Up</div>
        <div class = "basic center btn">Center</div>
        <div class = "basic down btn">Down</div>
    </div>
    ```
    + 設定群組變化
    ```html
    <div class = "red large horizontal buttons">
        <div class = "btn">Left</div>
        <div class = "btn">Center</div>
        <div class = "btn">Right</div>
    </div>
    ```

### 2.2 圖標按鈕

* 有圖標的按鈕
* **舉例**
    ```html
    <div class="horizontal buttons">
        <div class="left btn"><i class="mail icon"></i></div>
        <div class="center btn"><i class="heart icon"></i></div>
        <div class="right btn"><i class="cloud icon"></i></div>
    </div>
    ```

---
## 3. 狀態

### 3.1 觸發

* 
* **舉例**
    ```html
    ```

### 3.2 不可用

* 
* **舉例**
    ```html
    ```

### 3.3 載入

* 
* **舉例**
    ```html
    ```

---
## 4. 變動

### 4.1 顏色

* 不同顏色的按鈕
* **舉例**
    ```html
    <button class="red btn">Red</button>
    <button class="orange btn">Orange</button>
    <button class="yellow btn">Yellow</button>
    <button class="olive btn">Olive</button>
    <button class="green btn">Green</button>
    <button class="teal btn">Teal</button>
    <button class="blue btn">Blue</button>
    <button class="violet btn">Violet</button>
    <button class="purple btn">Purple</button>
    <button class="pink btn">Pink</button>
    <button class="brown btn">Brown</button>
    <button class="grey btn">Grey</button>
    <button class="black btn">Black</button>
    ```

### 4.2 大小

* 不同大小的按鈕
* **舉例**
    ```html
    <button class="small btn">Small</button>
    <button class="medium btn">Medium</button>
    <button class="large btn">Large</button>
    ```

### 4.3 切換

* 
* **舉例**
    ```html
    ```

### 4.4 正向

* 
* **舉例**
    ```html 
    <div class = "positive btn">Positive</div>
    ```

### 4.5 負向

* 
* **舉例**
    ```html
    <div class = "Negative btn">Negative</div>
    ```

### 4.6 流體

* 
* **舉例**
    ```html
    ```

### 4.7 圓

* 
* **舉例**
    ```html
    ```

### 4.8 水平附加

* 
* **舉例**
    ```html
    ```

### 4.9 垂直附加

* 
* **舉例**
    ```html
    ```

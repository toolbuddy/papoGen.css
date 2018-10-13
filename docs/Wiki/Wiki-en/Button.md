> Elements / Button

A button is going to trigger an action.

* **Prefix:** `btn`
* **Default**

    | Default | Name | Description |
    |---|---|---|
    | Button | `btn` | A standard button, as default |

* **Attributes**

    | Attributes | Name | Description |
    |---|---|---|
    | Primary | `primary` | Primary button |
    | Secondary | `secondary` | Secondary button |
    | Basic | `basic` | Basic design of a button with a frame|
    | Labeled | `labeled` | A Button that have a label |
    | Group | `buttons` | Buttons can exist together as a group |
    | Horizontal | `horizontal` | Horizontally grouped buttons |
    | Vertical | `vertical` | Vertically grouped buttons |
    | Up | `up` | A button with no bottom border radius |
    | Down | `down` | A button with no top border radius |
    | Center | `center` | A button with no border radius |
    | Left | `left` | A button with no right border radius |
    | Right | `right` | A button with no left border radius |
    | Small | `small` | Small button |
    | Medium | `medium` | Medium button, default size |
    | Large | `large` | Larger button |



---
## 1. Types

### 1.1 Default

* Default Button
* **Example**
    ```html
    <div class = "btn"></div>
    ```
* Primary Button
* **Example**
    ```html
    <div class = "primary btn"></div>
    ```
* Secondary Button
* **Example**
    ```html
    <div class = "secondary btn"></div>
    ```

### 1.2 Basic

* Simple design of a button
* **Example**
    ```html
    <div class = "basic btn"></div>
    ```

### 1.3 Inverted

* 
* **Example**
    ```html
    ```

### 1.4 Icon

* button with only icon
* **Example**
    ```html
    <div class = "basic btn">
        <i class = "icon cloud"></i>
    </div>
    ```
* button with text and icon
* **Example**
    ```html
    <div class = "basic btn">
        <i class = "left icon cloud"></i> cloud
    </div>
    <div class = "basic btn">
        cloud <i class = "right icon cloud"></i>
    </div>
    ```

### 1.5 Label

* A button with label on its left
* **Example**
    ```html
    <div class = "labeled btn"> 
        <div class = "basic button">
            <i class = "left icon mail"></i> mail
        </div>
        <div class = "label">receive</div>
    </div>
    ```

### 1.6 Labeled Icon

* 
* **Example**
    ```html
    ```

### 1.7 Animated

* 
* **Example**
    ```html
    ```

---
## 2. Groups

### 2.1 Buttons

* Buttons can exist together as a group
* **Example**
    + horizontal grouped buttons
    ```html
    <div class = "horizontal buttons">
        <div class = "basic left btn">Left</div>
        <div class = "basic center btn">Center</div>
        <div class = "basic right btn">Right</div>
    </div>
    ```
    + vertical grouped buttons
    ```html
    <div class = "vertical buttons">
        <div class = "basic up btn">Up</div>
        <div class = "basic center btn">Center</div>
        <div class = "basic down btn">Down</div>
    </div>
    ```
    + Set grouped variations 
    ```html
    <div class = "red large horizontal buttons">
        <div class = "btn">Left</div>
        <div class = "btn">Center</div>
        <div class = "btn">Right</div>
    </div>
    ```

### 2.2 Icon Buttons

* A button can have an icon
* **Example**
    ```html
    <div class="horizontal buttons">
        <div class="left btn"><i class="mail icon"></i></div>
        <div class="center btn"><i class="heart icon"></i></div>
        <div class="right btn"><i class="cloud icon"></i></div>
    </div>
    ```

---
## 3. States

### 3.1 Active

* 
* **Example**
    ```html
    ```

### 3.2 Disabled

* 
* **Example**
    ```html
    ```

### 3.3 Loading

* 
* **Example**
    ```html
    ```

---
## 4. Variations

### 4.1 Colored

* A button can have different colors
* **Example**
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

### 4.2 Size

* A button can have different sizes
* **Example**
    ```html
    <button class="small btn">Small</button>
    <button class="medium btn">Medium</button>
    <button class="large btn">Large</button>
    ```

### 4.3 Toggle

* 
* **Example**
    ```html
    ```

### 4.4 Positive

* 
* **Example**
    ```html 
    <div class = "positive btn">Positive</div>
    ```

### 4.5 Negative

* 
* **Example**
    ```html
    <div class = "Negative btn">Negative</div>
    ```

### 4.6 Fluid

* 
* **Example**
    ```html
    ```

### 4.7 Circular

* 
* **Example**
    ```html
    ```

### 4.8 Horizontal Attached

* 
* **Example**
    ```html
    ```

### 4.9 Vertical Attached

* 
* **Example**
    ```html
    ```
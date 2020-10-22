# Beginner-Vue-Style-Guide
Simple rules my styling in Vue should abide by

### Updated: 10/21/2020
<hr>

### Components
- **Component Names:** 
    - ke-bab / PascalCase
    - Multiword
    
- **Component File Names:**
    - ke-bab / PascalCase 
    
- Each component should be in its **file**

- Components **used once per page** and **don't accept props** should begin with **"The"**
    - TheHeading.vue 

- **Child Components** closely related to **Parent Components** should have **Parent Component Name**
    - components/
    - TodoList.vue
    - TodoListItem.vue
    
- **Component names** should start with **most general words** and end with **descriptive words**

<hr>

### Miscellaneous

- **Event Names:** kebab-case

- Use **key** with **v-for**

- **Styles (Single file):** Use **scoped** or **module**

- **Shortcuts:**
    - v-bind - **:**
    - v-on - **@**
    - v-slot - **#**
  
- Data **must be a function** to return **multiple instances**

- **You should use "props" this way:**
    - Props: {<br>
        status: {<br>
          type: String<br>
          
          /* 
          Whatever is in here
          
          */
        }<br>
      }
      
<hr>

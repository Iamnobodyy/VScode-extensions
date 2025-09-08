# VScode-extensions 小郭的分享以及懶人包
1. Material Icon Theme
   ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/Material%20Icon%20Theme1.png?raw=true)  
   使用方式：  
   按ctrl+shift+P，輸入Material Icons  
   ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/Material%20Icon%20Theme2.png?raw=true)  
   就可以在這裡挑選喜歡的icon顏色  

   或者按ctrl+shift+P，輸入open user settings (json)，進到srtting.json，使用手動改寫的方式修改喜歡的顏色  
   範例：  
   "material-icon-theme.folders.color": "#ef5350",  
   "material-icon-theme.files.color": "#42a5f5",  
   這是我的：  
   ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/Material%20Icon%20Theme3.png?raw=true)  
   效果：  
   ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/Material%20Icon%20Theme4.png?raw=true)  
   左邊的icon會變顏色  
   （小缺點，會一直要你買premium，只要打叉就好了）  
2. background  
   ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/backgroound1.png?raw=true)  
   改變背景，可以改這些地方：  
   ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/backgroound2.png?raw=true)  
   這是我的背景：  
   ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/backgroound3.png?raw=true)  
   程式碼（一樣貼在setting.json）：  
       "background.enabled": true,  
    "background.useDefault": false,  
    "background.customImages": [  
   你的圖片路徑  
   ]  
    "background.style": {  
    "content": "''",  
    "pointer-events": "none",  
    "position": "fixed",  
    "z-index": "99999",  
    "top": "0",  
    "left": "0",  
    "width": "100vw",  
    "height": "100vh",  
    "background-position": "center center",  
    "background-repeat": "no-repeat",  
    "background-size": "cover",  
    "opacity": 0.04  
    },  
    "material-icon-theme.activeIconPack": "angular",  
    "workbench.editor.empty.hint": "hidden",  

3. Code Runner  
   ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/coderunner1.png?raw=true)  
   支援執行程式碼片段  
   使用方式：  
   反白你要執行的程式碼，按"Run Code"  
   ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/coderunner2.png?raw=true)  
   結果：  
   ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/coderunner3.png?raw=true)

4. 

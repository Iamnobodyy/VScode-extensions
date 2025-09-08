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
   這是我的，我是用挑的不是手動改的：  
   ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/Material%20Icon%20Theme3.png?raw=true)  
   效果：  
   ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/Material%20Icon%20Theme4.png?raw=true)  
   左邊的icon會變顏色  
   
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

3. Code Runner  
   ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/coderunner1.png?raw=true)  
   支援執行程式碼片段  
   使用方式：  
   反白你要執行的程式碼，按"Run Code"  
   ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/coderunner2.png?raw=true)  
   結果：  
   ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/coderunner3.png?raw=true)  

4. Highlight Matching Tag  
   ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/Highlight1.png?raw=true)  
   當鼠標指向（或反白）程式碼時，與其相同的程式碼會被標註  
   ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/Highlight2.png?raw=true)  

5. Image Preview  
   ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/Image%20Preview1.png?raw=true)  
   可以預覽圖片，我覺得方便的點是可以立刻看出圖片路徑有沒有打錯（打錯就預覽不了）  
   結果：  
   ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/Image%20Preview2.png?raw=true)  

6. Indent-Rainbow  
   ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/rainbow1.png?raw=true)  
   不同層級的程式碼前面的顏色會不一樣  
   ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/rainbow2.png?raw=true)  

7. Monokai Pro  
   ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/Monokai%20Pro1.png?raw=true)  
   有超級多主題跟icon可以挑，我的藍色主題就是在這挑的~  
   使用方法：  
   按ctrl+shift+P，輸入Monokai  
   ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/Monokai%20Pro2.png?raw=true)  
   （小缺點，會一直要你買premium，只要打叉就好了）  

8. Path Autocomplete  
   ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/Path%20Autocomplete1.png?raw=true)  
   可以直接點資料夾or檔案，不需要複製路徑  
   ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/Path%20Autocomplete2.png?raw=true)  
   程式碼（setting.json）：  
   "path-autocomplete.pathMappings": {  
        "@src": "${folder}/src", // alias for @src  
    },  

9. Power Mode  
   ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/Power%20Mode1.png?raw=true)  
   打字效果：  
   ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/Power%20Mode2.png?raw=true)  
   程式碼：  
   "powermode.enabled": true,  
    "powermode.explosions.maxExplosions": 1,  
    "powermode.shake.intensity": 1,  
    "powermode.combo.counterSize": 0,  
    "powermode.combo.timerEnabled": "hide",  
    "powermode.explosions.offset": 0.22,  
    "powermode.shake.enabled": false,  
    "powermode.explosions.backgroundMode": "image",  
    "powermode.explosions.frequency": 1,  
    "powermode.explosions.customCss": {  
    "top": "0px",  
    },  
    "powermode.explosions.gifMode": "continue",  
    "powermode.explosions.size": 5,  
    "powermode.explosions.duration": 400,  
    "powermode.explosions.customExplosions": [  
    "https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExYzU4eXExZzZsMjlwZzIxYnAzdXUwbjVtY3d3cm5qeGoweHkzcnN2ZiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/1fhj2RprUOpqCObj2J/giphy.gif",
    ],  
   更多範例：  
   https://github.com/hoovercj/vscode-power-mode/issues/1  

10. Rainbow CSV  
    ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/Rainbow%20CSV1.png?raw=true)  
    將CSV檔的每一行用不同顏色區分，之前機器學習很常用到，如果你不常用到可以略過  
    結果：  
    ![image](https://github.com/Iamnobodyy/VScode-extensions/blob/main/images/Rainbow%20CSV2.png?raw=true)

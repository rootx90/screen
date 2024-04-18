# screen
``` bash
 screen
```
 ## to open screen in terminal.
*   ```ctrl+a then ctrl+d to screen deattacch``` "يعني هتختفي من الشاشة بس هتقعد شغالة في الخلفية ".

*  وعلشان ترجعها تاني تكتب الامر ده  
``` bash
screen -ls
```
* الامر ده هيعرض عليك ```screen```اللي مفتوحين عندك.
* بعدين تكتب الامر ده ```screen -r (screen -id)``` للإسترجاع المطلوب ب ID.
  
To terminate a screen session with ID 243, you can use the `kill` command along with the screen session ID. Here's how to do it:

```bash
screen -X -S 243 quit
```

This command sends a quit signal to the screen session with the specified ID (243), effectively terminating it.

1. 转换 es6.js 文件并在当前命名行程序窗口中输出

    ```
    babel es6.js
    ```

2. 将 es6.js 转换后输出到 es5.js 文件中（使用 -o 或 --out-file ）

    ```
    babel es6.js -o es5.js
    babel es6.js --out-file es5.js
    ```

3. 实时监控 es6.js 一有变化就重新编译（使用 -w 或 --watch ）

    ```
    babel es6.js -w --out-file es5.js
    babel es6.js --watch --out-file es5.js
    ```

4. 编译整个 src 文件夹并输出到 lib 文件夹中（使用 -d 或 --out-dir ）

    ```
    babel src -d lib
    babel src --out-dir lib
    ```

5. 编译整个 src 文件夹并输出到一个文件中

    ```
    babel src --out-file es5.js
    ```

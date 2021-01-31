### DevTools - Debugging
Screenshots of the watch expressions list, breakpoints list, and the bug fix are in the part3 folder.

1. The bug was that the data type of the variables num1 and num2 was string as they were initialized using document.getElementById. So when finding the sum of those two variables, string concatenation was performed. So, result was a string concatenation of num1 and num2.
2. To fix it, convet num1 and num2 to numbers using the Number() function.

### DevTools - Network Tab
1. The name of the new json file is citylots.json
2. The file part2.js initiated the download of the new file.
3. The file size is 11.7MB.
4. It took 2.22 seconds to download the file.
5. The User-Agent for the browser that made the request is Mozilla/5.0 (Linux; Android 6.0; Nexus 5 Build/MRA58N) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/88.0.4324.96 Mobile Safari/537.36
6. The response came from an Apache server.
7. The file was last modified on Tue, 26 Jan 2021 22:14:13 GMT.
8. The Content-Type of the file was application/json.
9. The method fetchData() inside the initiating file made the request.

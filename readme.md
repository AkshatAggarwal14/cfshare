# A Repository to Help In Sharing Our Starred Codeforces Problems
## How To Save Bookmarklets
1. Press ctrl+shift+b to display bookmark bar
2. Drag these import and export links to bookmark bar.

<a href="javascript:(function() {let input=prompt('Paste the problems to import');let problems=input.split(',');document.body.innerHTML='';problems.forEach(id=>buttonFromId(id));function buttonFromId(problemId){let link=`https://codeforces.com/contest/${parseInt(problemId)}/problem/${problemId.replace(/^\d+/,'')}`;let htmlTemplate=`<a href='${link}'> Problem ${problemId} </a><br><br>`;document.body.innerHTML+=htmlTemplate;}})()">Import</a>

<a href="javascript:(function () {let problems=[];let elements=document.querySelectorAll('td.id.left');elements.forEach(e=>problems.push(e.innerText));prompt('ctrl+c to copy',String(problems))})()">Export</a>
> above links not active ? they must be active on https://lkithakur.github.io/cfshare/

## How To Export Favourite Questions 
1. Go To [https://codeforces.com/favourite/problems](https://codeforces.com/favourite/problems) (make sure your favourite problems are showing on page)
2. Click on Export Bookmarklet Link
3. Copy and share the text containing list of problems

> bookmarklets can not be used from the new tab page due to security reasons; navigate to any webpage to use them  

## How To Import 
1. click on import bookmarklet 
2. use the text from step 3 when prompted

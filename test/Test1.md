# Image tag rendering test

**1.  Test img tag without '/' in same folder path:**

<img src="img/SystemAccount.png" width="500px" height="400px">

**2.  Test img tag with '/' relative path**

<img src="/test/img/SystemAccount.png" width="500px" height="400px">

**3.  Test img tag with './' relative path**

<img src="./img/SystemAccount.png" width="500px" height="400px">

**4.  Test img tag with '../' relative path**

<img src="../test/img/SystemAccount.png" width="500px" height="400px">

**5.  Test img tag with 'https' absolute path**

<img src="https://raw.githubusercontent.com/AvikChakraborty18/testGitContent/refs/heads/main/test/img/SystemAccount.png" width="500px" height="400px">

**6.  Test img tag enclosed within [] (a href tag) - On clicking image, the image in github should open**

[<img src="img/SystemAccount.png" width="600" />](img/SystemAccount.png)


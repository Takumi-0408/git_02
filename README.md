##git log --oneline
9241ca4 (HEAD -> main, origin/main, origin/HEAD) 修正２
9468750 修正
ec64f99 色追加
01e49eb style.css追加
a075999 自己紹介追加
e84c9a8 index.html追加
6dbb474 README.md追加

##git show
PS C:\Projects\GitLesson\git_02> git show 6dbb474
commit 6dbb474c1d858b345f3355ee6620184f41ad9c54
Author: Takumi-0408 <kss-25210120@nsgcl.jp>
Date:   Tue Nov 17 14:50:21 2026 +0900

    README.md追加

diff --git a/README.md b/README.md
new file mode 100644
index 0000000..e69de29
PS C:\Projects\GitLesson\git_02> git show e84c9a8
commit e84c9a8ba4db11ff168b9aed85bcbe43775399f1
Author: Takumi-0408 <kss-25210120@nsgcl.jp>
Date:   Tue Nov 17 14:56:39 2026 +0900

    index.html追加

diff --git a/index.html b/index.html
new file mode 100644
index 0000000..4812c0b
--- /dev/null
+++ b/index.html
@@ -0,0 +1,10 @@
+<!DOCTYPE html>
+<html lang="ja" dir="ltr">
+    <head>
+        <meta charset="utf-8">
+        <title></title>
+    </head>
+    <body>
+        <h1>林巧望です</h1>
+    </body>
+</html>
\ No newline at end of file
PS C:\Projects\GitLesson\git_02> git show a075999
commit a075999489c7dbffe4d3f19c46081f9df579a761
Author: Takumi-0408 <kss-25210120@nsgcl.jp>
Date:   Tue Nov 17 14:57:23 2026 +0900

    自己紹介追加

diff --git a/index.html b/index.html
index 4812c0b..94b3e19 100644
--- a/index.html
+++ b/index.html
@@ -2,7 +2,7 @@
 <html lang="ja" dir="ltr">
     <head>
         <meta charset="utf-8">
-        <title></title>
+        <title>自己紹介</title>
     </head>
     <body>
         <h1>林巧望です</h1>
PS C:\Projects\GitLesson\git_02> git show 01e49eb
commit 01e49eb74d7da9ee4765193fe268f7bec92f9abc
Author: Takumi-0408 <kss-25210120@nsgcl.jp>
Date:   Tue Nov 17 14:59:07 2026 +0900

    style.css追加

diff --git a/style.css b/style.css
new file mode 100644
index 0000000..e69de29
PS C:\Projects\GitLesson\git_02> git show ec64f99
commit ec64f99fc625d6e07e7ba47ba3abf0f511caf5a8
Author: Takumi-0408 <kss-25210120@nsgcl.jp>
Date:   Tue Nov 17 14:59:56 2026 +0900

    色追加

diff --git a/style.css b/style.css
index e69de29..6435481 100644
--- a/style.css
+++ b/style.css
@@ -0,0 +1,5 @@
+@charset "utf-8";
+
+h1{
+    color:red;
+}
\ No newline at end of file
PS C:\Projects\GitLesson\git_02> git show 9468750 
commit 94687504c2bfe707b1145c371c6f8c7a2926a9e0
Author: Takumi-0408 <kss-25210120@nsgcl.jp>
Date:   Tue Nov 17 15:02:15 2026 +0900

    修正

diff --git a/index.html b/index.html
index 94b3e19..011d95e 100644
--- a/index.html
+++ b/index.html
@@ -3,6 +3,7 @@
     <head>
         <meta charset="utf-8">
         <title>自己紹介</title>
+        <link rel="stylesheet" href="css/style.css">
     </head>
     <body>
         <h1>林巧望です</h1>
PS C:\Projects\GitLesson\git_02> git show 9241ca4
commit 9241ca42ea6e91db3d2577d0588b23dda49f3c54 (HEAD -> main, origin/main, origin/HEAD)
Author: Takumi-0408 <kss-25210120@nsgcl.jp>
Date:   Tue Nov 17 15:03:15 2026 +0900

    修正２

diff --git a/index.html b/index.html
index 011d95e..d0e332f 100644
--- a/index.html
+++ b/index.html
@@ -3,7 +3,7 @@
     <head>
         <meta charset="utf-8">
         <title>自己紹介</title>
-        <link rel="stylesheet" href="css/style.css">
+        <link rel="stylesheet" href="style.css">
     </head>
     <body>
         <h1>林巧望です</h1>
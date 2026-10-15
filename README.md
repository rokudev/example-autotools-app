# example-autotools-app has moved to GitLab

**This project has moved.** Development now continues at **https://gitlab.com/rokudev/example-autotools-app**.

This GitHub repository is archived and read-only. It is kept only as a pointer to the new home. Please open new issues and merge requests on GitLab.

---

# Example Autotools Application

This one uses the example Autotool's lib and CMake lib as dependencies to create: `buzz_aldrin`

This app has an intentional coding bug for our "Hello Universe" example:

```diff
diff --git a/src/buzz.cpp b/src/buzz.cpp
index 1dddaee..97ec7e7 100644
--- a/src/buzz.cpp
+++ b/src/buzz.cpp
@@ -1,6 +1,4 @@
-#include <string>
-#include <vector>
-#include <algorithm>
+#include <iostream>

 #include <jupiter.h>

```

<div dir="rtl" lang="he">

# עץ משפחה - שלב א

כתבו מחלקה המייצגת עץ משפחה - עץ הורים של אדם אחד.

כדי לראות איך המחלקה אמורה לעבוד, ראו בקובץ
Demo.cpp
המצורף.


בשלב א עליכם לכתוב את הקבצים הדרושים כך שהפקודות הבאות יעבדו ללא שגיאות קימפול:

<div dir='ltr'>

    make demo && ./demo
	make test && ./test

</div>


* addFather - הוספת אב למישהו שכבר נמצא בעץ.
* addMother - הוספת אם למישהו שכבר נמצא בעץ.
* relation - מקבלת שם של מישהו שנמצא בעץ, ומחזירה את היחס בינו לביניכם. למשל: father, mother, grandmother, great-grandfather, great-great-grandmother... אם הוא לא נמצא בעץ יש להחזיר unrelated.
* find - הפונקציה ההפוכה - מקבלת מחרוזת המציינת יחס כמו למעלה, ומחזירה את שם האדם מהעץ המקיים יחס זה.
* display - הצגת העץ, לצורך הדגמה וניפוי שגיאות. פורמט התצוגה - לבחירתכם.
* remove - מקבלת שם של מישהו שנמצא בעץ, ומוחקת אותו ואת כל ההורים שלו מהעץ.

</div>

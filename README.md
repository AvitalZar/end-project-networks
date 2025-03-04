# פרויקט סיום רשתות תקשורת
פרוייקט זה הוא חלק מתכנית הלימודים שלנו בקורס רשתות תקשורת באוניברסיטת אריאל.  
מגישות הפרוייקט: אביטל זר, יעל גיל דורני, עדי גם זו לטובה, ושירה מרסיאנו.

הפרוייקט סוקר סיווג של תעבורת רשת. הוא מורכב משלושה חלקים:  
חלק מספר 1: שאלות פתוחות על ידע בסיסי על מאפייני תעבורת רשת.  
חלק מספר 2: מכיל שלושה מאמרים שקראנו, סיכמנו ובחנו את תרומתם לנושא.  
חלק מספר 3: החלק המעשי.   
היה מורכב מארבעה חלקים:  
1\. מעקב אחרי תעבורת רשת בעת פתיחת יישומים שונים.   
2\. עיבוד התעבורה לגרפים.  
3\. ניתוח הגרפים והסקת מסקנות לגבי היישומים השונים בהקשר של תעבורה   
4\. הסבר על איך אפשר ללמוד על היישומים המשומשים על פי התעבורה.

הפרויקט נפרש על שתי תיקיות: res המכילה את הגרפים, התשובות והסיכומים, ותיקיית src שמכילה את הקוד.  
בתיקיה res קיימים שני קבצים:

1) קובץ בשם החלקים הכתובים בו יש תשובות לשאלות וסיכומים,   
2) קובץ בשם חלק 3 ניתוח גרפים בו יש גרפים של קבצי הקלטה שונים וניתוחם.  
     
   

הוראות הרצת קוד:

הקוד כתוב בפייתון. על מנת שהקוד ירוץ כראוי צריכות הספריות הבאות להיות מותקנות על המערכת:  
pyshark, pandas, matplotlib, numpy, seaborn, acetools.  
נוסף על כך, כדי שהקובץ ירוץ על לינוקס ייתכן שיהיה צריך להתקין את tshark.  
בתחילת הקוד מוגדר נתיב התיקיה בה משתמשים. על מנת שהקוד יעבוד כראוי על תיקיות אחרות במחשבים אחרים, יש לשנות את הנתיב הזה.   
\[(desktop\_path \= os.path.expanduser("\~/Desktop/res"  
\#במידה והתיקיה נמצאת במקום אחר יש לעדכן את הקוד ידנית\]  
בתיקייה צריכים להיות קבצי הpcap הבאים: chrome\_record, firefox\_record, spotify\_record, youtube\_record, zoom\_record.

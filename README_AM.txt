Jcbhi Mobile - Android Studio starter project

ይህ ፕሮጀክት የJcbhi ድረ-ገጽን በAndroid WebView ውስጥ የሚከፍት መነሻ ፕሮጀክት ነው። የተጠናቀቀ APK ወይም Google Play Store ላይ የተለቀቀ መተግበሪያ አይደለም።

ለመገንባት:
1. በኮምፒውተር Android Studio ጫን።
2. ይህን ZIP አውጣና Android Studio ውስጥ ክፈት።
3. Gradle sync እንዲጨርስ ጠብቅ።
4. በAndroid ስልክ ወይም emulator ላይ Run በማድረግ ሞክር።
5. ለPlay Store ማቅረብ ከመቻልህ በፊት በትክክለኛ መሳሪያዎች ሞክር፣ የPrivacy Policy አዘጋጅ፣ Data safety መረጃ ሙላ፣ እና Play Console የሚጠይቀውን የማቅረቢያ ሂደት ጨርስ።

አስፈላጊ:
- ይህ app የህክምና/ሪፈራል መረጃ ሊያሳይ ስለሚችል፣ የWeb App መግቢያ እና የፈቃድ መቆጣጠሪያዎች በserver በትክክል መጠበቃቸውን አረጋግጥ።
- የመነሻ URL ከapp/src/main/java/com/jcbhi/mobile/MainActivity.kt ውስጥ ተዘጋጅቷል።
- ከGoogle Play ለማቅረብ የPlay Console መለያ እና የGoogle የአሁኑ መመሪያዎች ያስፈልጋሉ።
ስልክ ብቻ በመጠቀም cloud build:
1. GitHub ላይ አካውንት ክፈት/ግባ እና አዲስ repository ፍጠር።
2. ZIP ን በስልክህ extract አድርግ። የውስጡን ፋይሎች ወደ repository አፕሎድ አድርግ፤ የፕሮጀክት ፋይሎች በrepository root ላይ መሆን አለባቸው።
3. GitHub repository ውስጥ Actions tab ግባ። የworkflow ፋይሉ .github/workflows/android-build.yml ውስጥ አለ።
4. በActions ውስጥ “Build Jcbhi Android APK” ምረጥ፣ “Run workflow” ተጫን፣ ከዚያ የሚሰራውን run ክፈት።
5. ስራው ከተሳካ ከታች Artifacts ውስጥ jcbhi-debug-apk አውርድ።

ይህ debug APK ለሙከራ ብቻ ነው። Google Play Store ለማቅረብ signed release AAB, privacy policy, data safety declaration, testing እና Play Console setup ያስፈልጋሉ።

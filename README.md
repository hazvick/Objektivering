Objektivering

För att start programmet korrekt, följ dessa steg.  
1.) File > Project Structure > Libraries > ***välj javaFX lib***  
2.) I build settings > Edit configurations > i VM options, klistra in följande:  
-p  
C:\ ***DinPathTillJavaFXHär*** \javafx-sdk-17\lib  
--add-modules  
javafx.controls,javafx.fxml  
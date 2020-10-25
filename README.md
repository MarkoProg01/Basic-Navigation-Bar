# Basic-Navigation-Bar
<h3>IZGLED MENIJA:</h3>


<img src="screenshot/Snimak%20ekrana%20(6).png" width="300" height="600">


 
 <dl>
  <dt>Podešavanje</dt>
  <dd>U **build.gradle** implementirati sledeći deo koda:</dd>
  </dl>
  
  
  `implementation 'com.github.armcha:SpaceNavigationView:1.6.0'`
 
 
 <dl>
  <dt>Dodavanje ikonica u <b>drawable</b> folder</dt>
 <dd>Dodavanje se vrši desnim klikom na folder <b>drawable--> new-->Vector Assets</b></dd>
  <dd>U folder drawable dodati sledeće ikonice: </br> 1. add </br> 2. favourite </br> 3. history </br> 4. home </br> 5. settings </dd>
  </dl>
  
  <h3>activity_main.xml fajl</h3>
  
  <p>Prvo što dodajemo je <b>TEXT VIEW</b> </p>
  
  ```
 
 <TextView

        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World!"
        android:layout_centerInParent="true"
        android:textSize="35sp"
        android:textColor="#F0F0F0"
        android:textAllCaps="true"
        android:textStyle="bold|italic"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent" />
        ```
  

<!-- Headings -->
# Animated Navigation Bar 



<!-- Strong -->
Ovaj **Navigation Bar** je vrlo lep i ima prelaz.
___
## Izgled
<img src="screenshot/Snimak%20ekrana%20(6).png" width="300" height="600">

## Zadaci
* [ ] Implementacija koda u Javu
* [ ] Implementacija koda u xml fajl
* [ ] Pokretanje programa bez i jedne greške
___
## Kod
### Prvo ćemo povezati **chipNavigationBar** sa njegovig **ID** i staviti da **HomeFragment** bude podrazumevan.
```java
  chipNavigationBar = findViewById(R.id.chipNavigation);

        chipNavigationBar.setItemSelected(R.id.home,true);
        getSupportFragmentManager().beginTransaction().replace(R.id.container,new HomeFragment()).commit();
```
* [x] Implementacija koda u Javu
* [ ] Implementacija koda u xml fajl
* [ ] Pokretanje programa bez i jedne greške
### Zatim ćemo u **xml fajl** dodati sledeći deo koda:
```xml
 <com.ismaeldivita.chipnavigation.ChipNavigationBar
        android:id="@+id/chipNavigation"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        app:cnb_menuResource="@menu/nav_item"
        />
```
* [x] Implementacija koda u Javu
* [x] Implementacija koda u xml fajl
* [ ] Pokretanje programa bez i jedne greške

<!-- Tables -->
| Mreža     | Kontakt                    |
| -------- | -------------------------|
| Gmail| mmirkov2706@gmail.com |
| Instagram | m_mirkov01|

<!-- Task List -->
* [x] Implementacija koda u Javu
* [x] Implementacija koda u xml fajl
* [x] Pokretanje programa bez i jedne greške
____

# Breast Cancer Awareness App (by Cheon, Nihalani, Po)
breastcancerawarenessapp-rybackpo created by Classroom for GitHub

This app is to inform Filipinos about the importance of Breast Cancer which is the top cause of death of the people in the Philippines. it shows statistics and definition of the breast cancer together with its causes and ways to prevent it.

## Problem:

Design and implement an android app with a splash animation, a toplevel menu, a category menu and a help, which uses an external text file as the display text.

## Features:

- Splash Screen Activity
- Text to Speech
- Facebook Sharing
- Background Music
- Sliding/Tab View

## Sample Solution:

https://github.com/DeLaSalleUniversity-Manila/breastcancerawarenessapp-rybackpo

## Keypoints:

From TopLevelMenu
```Java
        CustomList adapter = new CustomList(TopLevelMenu.this, topmenu, imageId);
        ListView menuList = (ListView) findViewById(R.id.toplevelListView);
        menuList.setAdapter(adapter);
        menuList.setOnItemClickListener(new AdapterView.OnItemClickListener() {
            @Override
            public void onItemClick(AdapterView<?> parent, View view, int position, long id) {
                if (position == 0) {
                    Intent toInformation = new Intent(TopLevelMenu.this, Information.class);
                    startActivity(toInformation);
                } else if (position == 1) {
                    Intent toCauses = new Intent(TopLevelMenu.this, Causes.class);
                    startActivity(toCauses);
                } else if (position == 2) {
                    Intent toPrevention = new Intent(TopLevelMenu.this, Prevention.class);
                    startActivity(toPrevention);
                } else if (position == 3) {
                    Intent toMoreInfo = new Intent(TopLevelMenu.this, ForMoreInfo.class);
                    startActivity(toMoreInfo);
                } else if (position == 4) {
                    Intent toHelp = new Intent(TopLevelMenu.this, Help.class);
                    startActivity(toHelp);
                }
                onClick(position);
            }
        });
```

## Screenshots:

##### Splash Activity
![alt tag](https://github.com/DeLaSalleUniversity-Manila/breastcancerawarenessapp-rybackpo/blob/master/Splash%20Activity.png)

##### Top Level Menu
![alt tag](https://github.com/DeLaSalleUniversity-Manila/breastcancerawarenessapp-rybackpo/blob/master/Top%20Level%20Menu.png)

##### Information_History
![alt tag](https://github.com/DeLaSalleUniversity-Manila/breastcancerawarenessapp-rybackpo/blob/master/Information-History.png)

##### Information_Statistics
![alt tag](https://github.com/DeLaSalleUniversity-Manila/breastcancerawarenessapp-rybackpo/blob/master/Information-Statistics.png)

##### Information_Treatment
![alt tag](https://github.com/DeLaSalleUniversity-Manila/breastcancerawarenessapp-rybackpo/blob/master/Information-Treatment.png)

##### Causes_Foods
![alt tag](https://github.com/DeLaSalleUniversity-Manila/breastcancerawarenessapp-rybackpo/blob/master/Causes-Foods.png)

##### Causes_Drinks
![alt tag](https://github.com/DeLaSalleUniversity-Manila/breastcancerawarenessapp-rybackpo/blob/master/Causes-Drinks.png)

##### Causes_Environment
![alt tag](https://github.com/DeLaSalleUniversity-Manila/breastcancerawarenessapp-rybackpo/blob/master/Causes-Environment.png)

##### Causes_Habits
![alt tag](https://github.com/DeLaSalleUniversity-Manila/breastcancerawarenessapp-rybackpo/blob/master/Causes-Habits.png)

##### Prevention_Foods
![alt tag](https://github.com/DeLaSalleUniversity-Manila/breastcancerawarenessapp-rybackpo/blob/master/Prevention-Foods.png)

##### Prevention_Drinks
![alt tag](https://github.com/DeLaSalleUniversity-Manila/breastcancerawarenessapp-rybackpo/blob/master/Prevention-Drinks.png)

##### Prevention_Environment
![alt tag](https://github.com/DeLaSalleUniversity-Manila/breastcancerawarenessapp-rybackpo/blob/master/Prevention-Environment.png)

##### Prevention_Habits
![alt tag](https://github.com/DeLaSalleUniversity-Manila/breastcancerawarenessapp-rybackpo/blob/master/Prevention-Habits.png)

##### For More Information
![alt tag](https://github.com/DeLaSalleUniversity-Manila/breastcancerawarenessapp-rybackpo/blob/master/For%20More%20Information.png)

##### Help
![alt tag](https://github.com/DeLaSalleUniversity-Manila/breastcancerawarenessapp-rybackpo/blob/master/Help.png)

##### Sliding/Tab View
![alt tag](https://github.com/DeLaSalleUniversity-Manila/breastcancerawarenessapp-rybackpo/blob/master/Slide%20Screen%20via%20Tab.png)

##### Facebook Sharing
![alt tag](https://github.com/DeLaSalleUniversity-Manila/breastcancerawarenessapp-rybackpo/blob/master/Facebook%20Sharing.png)

##### Shared App to Facebook
![alt tag](https://github.com/DeLaSalleUniversity-Manila/breastcancerawarenessapp-rybackpo/blob/master/Shared%20App%20to%20Facebook.png)

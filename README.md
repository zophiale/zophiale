# Zophia Horvath

```cpp
// ==!==!==!==!==!==!== //
// Zophia Horvath       //
// Undergrad Student    //
// Created:             //
// 03/04/2026           //
// Updated:             //
// 10/08/2026           //
// ==!==!==!==!==!==!== //

#include "user.h"

int main()
{ 

    user Zophia = new user();
    
    Zophia.setName("Zophia Horvath");
    Zophia.setEducationLevel(Education.UNDERGRAD.JUNIOR);
    Zophia.setUniversity(Universities.Salisbury);
    
    Zophia.addSkills(4,
            {
                "Enjoys a good headscratcher",
                "Sysadmin proficiency",
                "Energetic",
                "Leader"
            }
    );

    Zophia.setDescription("Hi! I'm Zophia, an undergraduate at Salisbury University!" +
"I have been studying programming to varying degrees for the past 14 years.");

    Zophia.assignDiscord("archaezalia", 478945907748896792);

    printf("%s", Zophia.fancystr());

    return 0;
}
```
![GitHub Stats Card](https://ghstats.dev/api/card?username=zophiale&theme=ayu)

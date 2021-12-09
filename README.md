# Breakfast
I had waffles with maple syrup and juice :waffle: 
[LinkedIn](https://www.linkedin.com/in/ethan-mcgrath-464596198/)
![Octocat](https://github.com/Emcg200/Week10PRODEV/blob/main/octocat.png)

##List of favourite games :video_game:
1. Minecraft
2. Subnautica

###List of things todo for ProDev
- [ ] Develop Website
- [ ] Research Report
- [ ] Write Report

Code from  Games Engine Creation:
```
   int num;
    string stars = "*";
    char choice = 'Y';
    do
    {
        cout << "Please enter a number.\n";
        cin >> num;
        for (int i = 0; i < num; i++)
        {
            cout << stars << endl;
            stars += '*';
        }
        stars = "*";
        cout << "Would you like to do that again? [Y/N]\n";
        cin >> choice;
        choice = toupper(choice);
        if (choice == 'N')
        {
            cout << "Goodbye!\n";
            break;
        }

    } while (choice == 'Y');
```

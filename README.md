# Temporary Elevated Access Management (AD)

# Description
This application provides a way to manage group memberships for AD that don't have supporting data for automation. This allows the Administrator (or Operator) to use the app to assign memberships directly with an option to expire. The memberships are then added to the role model as part of the normal operations so they are can be validated as normal and be enforced.

# Screenshots
![image](https://github.com/user-attachments/assets/2f2d0ba0-c137-46b5-80d5-8f8cee215de4)

![image](https://github.com/user-attachments/assets/e0e16e43-2250-4b94-ba05-b998f1e9b3eb)


# Installation
- Download backup repository
- Import backup repository
- Add "app_TEAM_Memberships" to Internal Systems
- Set "ID" as Key
- Set "Expiration_Date" as date "yyyy-mm-dd (local)"
- Restart service

# NIM Docs
The official NIM documentation can be found at: https://docs.nimsuite.com

# Active Directory Account Lockout Incident
<img width="1918" height="992" alt="Jira&#39;s ticket dashboard" src="https://github.com/user-attachments/assets/bbf1a1ee-d6c0-41b5-9501-27fa1ed854f5" />


## Issue
User unable to log in due to multiple failed login attempts.
<img width="1915" height="1018" alt="AD-ticket1-created" src="https://github.com/user-attachments/assets/feda6728-26f4-4154-88ed-077fcf210118" />


## Environment
Windows 10, Active Directory, Microsoft 365, Domain-joined device.
<img width="1918" height="863" alt="Ticket1-pending status" src="https://github.com/user-attachments/assets/a5873dad-8d11-484e-abf6-f99355c50470" />


## Troubleshooting Steps
1. Verified the issue with the user.
2. Checked account status in Active Directory.
3. Identified account lockout due to failed login attempts.
4. Reset password and unlocked the account.
5. Confirmed successful login with the user.![Uploading AD-ticket1-created.png…]()


## Root Cause
Multiple failed login attempts triggered security lockout policy.
<img width="1906" height="950" alt="ticket1-Ad-in-progress" src="https://github.com/user-attachments/assets/a7c1bd62-3ac4-497a-86fb-9461e5c73da4" />


## Resolution
Password reset and account unlocked. User regained access.
<img width="1918" height="1016" alt="ticket1-resolve-status" src="https://github.com/user-attachments/assets/05dbf4f9-20f6-4db3-85ef-0c4106de8d2c" />


## ITIL Process Followed
- Incident identification
- Troubleshooting
- Resolution
- Documentation
 <img width="1781" height="717" alt="ticket-1-final-workflow" src="https://github.com/user-attachments/assets/36c4279e-c4fe-4a58-bfdf-b788f2e68827" />


- Ticket closure
<img width="1918" height="960" alt="AD-ticket-closed" src="https://github.com/user-attachments/assets/d5d8bbb7-1580-403b-a354-bd1654cd8bcb" />
 


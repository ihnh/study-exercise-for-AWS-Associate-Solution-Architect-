### Creating a Secure IAM User

A secure IAM user is one configured following security best practices such as least privilege permissions, MFA enabled and given no unnecessary credentials.

Created a secure IAM user for backup administration.

![IAM User Setup](https://github.com/user-attachments/assets/80af0aff-e4bf-441f-bded-47eed95f5efe)

Attached policies with the permissions needed for backup tasks, including **S3 read-only access**. This follows the principle of least privilege:only granting what the user actually needs.

<img width="1828" height="779" alt="image" src="https://github.com/user-attachments/assets/4d31d958-842f-416a-ba2e-137d80733638" />

<img width="1817" height="802" alt="image" src="https://github.com/user-attachments/assets/ea1015fe-9990-4e81-9482-de66f16cc424" />

<img width="1841" height="196" alt="image" src="https://github.com/user-attachments/assets/e5b0b97f-c3cd-4985-b3bf-ec9513c682d0" />

Configured security credentials:**MFA** as the key authentication method. MFA requires both a password and a physical device, meaning an attacker would need the username, password, and access to the user's phone to gain entry.

<img width="1813" height="588" alt="image" src="https://github.com/user-attachments/assets/26b6a3e8-7a86-40f0-b9b1-ab1fef4235c9" />

<img width="975" height="874" alt="image" src="https://github.com/user-attachments/assets/4f965da6-074f-4bbc-ae57-16e5cc0c3abc" />

### What I learned
- A **secure IAM user** follows least privilege, enables MFA, and avoids unnecessary credentials
- IAM policies grant permissions - attach only what the user needs
- Credentials come in different forms: console password, access keys, and MFA
- MFA significantly reduces the risk of unauthorized access whereby a password alone is not enough

### Key services used
- IAM

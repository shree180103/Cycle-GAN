# Cycle-GAN

The key idea is to translate images between two domains (say domain X and domain Y) without having paired training examples. For example, you might have many horse images (domain X) and many zebra images (domain Y), but you do not have exact horse-to-zebra matching pairs. CycleGAN learns mappings both ways

<img width="521" height="119" alt="image" src="https://github.com/user-attachments/assets/d16c9296-fc23-4ce4-9557-8b7db54c8fb4" />

# Model architecture
Generator:


<img width="1599" height="658" alt="image" src="https://github.com/user-attachments/assets/894ef9f4-d13d-473d-903a-2312f71ff355" />

Dicriminator:


<img width="1361" height="735" alt="image" src="https://github.com/user-attachments/assets/28cd5b89-abbe-4914-9166-76681c256ec0" />

# Loss Functions

Gan loss:


<img width="458" height="64" alt="image" src="https://github.com/user-attachments/assets/1a26be3a-3ddb-4883-8ac2-5b639763cadc" />

cycle consistency loss:


<img width="422" height="85" alt="image" src="https://github.com/user-attachments/assets/5527b8bd-93a7-404e-bf6d-000946abc661" />

Full objective loss:


<img width="372" height="113" alt="image" src="https://github.com/user-attachments/assets/44212ccf-ccbf-45a1-b910-da7c48feaab2" />

#Results

<img width="458" height="389" alt="image" src="https://github.com/user-attachments/assets/1ec75645-6372-47cf-8659-9d1e97f78840" />

<img width="458" height="389" alt="image" src="https://github.com/user-attachments/assets/2910bf21-fc3a-455e-a825-b5629bd4e2fd" /> <img width="458" height="389" alt="image" src="https://github.com/user-attachments/assets/185edbd7-9338-459a-bff8-97f717635e64" />

<img width="458" height="389" alt="image" src="https://github.com/user-attachments/assets/008766b8-be49-40e5-8e00-1741bc83be15" />

<img width="458" height="389" alt="image" src="https://github.com/user-attachments/assets/84c058cb-af16-4f0a-9a96-4b44316e4008" />


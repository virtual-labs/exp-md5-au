### Theory  

MD5 (Message Digest Algorithm 5) is a cryptographic hash function that generates a fixed-size 128-bit hash value from an input of variable length. It is widely used for verifying data integrity by producing a unique hash that can be compared against an original reference. However, due to security vulnerabilities, such as collision attacks, MD5 is no longer considered secure for cryptographic applications.  

![MD5 Algorithm](./images/md5.png)  

#### Use of MD5 Algorithm 

- **File Authentication** – MD5 is commonly used to verify the authenticity and integrity of files. When a file is processed through the MD5 algorithm, it generates a unique hash value. By comparing this hash with a previously stored hash, users can determine whether the file has been modified.  
- **Web Application Security** – In the past, MD5 was used to secure user passwords by hashing them before storage. However, due to advancements in cracking techniques, such as rainbow table attacks, MD5 is now considered insecure for password protection.  
- **Password Storage** – Instead of storing passwords in plaintext, many systems historically used MD5 hashing to convert them into a 128-bit hash value. While this approach added a layer of security, modern cryptographic methods such as SHA-256 and bcrypt are now preferred due to MD5’s weaknesses.  
- **Data Integrity Checks** – MD5 is frequently used to detect accidental changes in files. When a file is transmitted or stored, its hash value can be computed before and after transmission. If the two hash values match, it confirms that the file remains unaltered.  

#### Applications of MD5 Algorithm

- **File Integrity Verification** – MD5 plays a crucial role in ensuring files remain unchanged by generating a unique hash for each file. Users can compare this hash against the original to confirm that no data corruption or unauthorized modifications have occurred.  
- **Digital Signatures** – MD5 was once used in cryptographic applications to sign and verify documents. It helped authenticate digital documents by generating a hash that could be used to detect any alterations. However, due to its vulnerabilities, it is now replaced by more secure hashing techniques like SHA-2.  
- **Password Verification** – In authentication systems, MD5 hashing was historically used to store and compare passwords. When a user enters a password, it is hashed and compared with the stored MD5 hash to verify login credentials. However, due to its susceptibility to attacks, it is no longer recommended for secure password storage.  
- **Gaming and Graphics** – Some game engines and graphics applications implement MD5 hashing for data management and verification. Hashes are used to ensure game files remain consistent and unmodified, preventing data corruption or tampering in gaming environments.  

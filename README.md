## `server.py` README

### Overview
The `server.py` script is the server-side component of a client-server chat application. It is responsible for handling incoming connections from clients, managing user authentication, and enabling secure communication within a chatroom.

### Instructions
1. Ensure that Python is installed on your system.

2. Install the required libraries using pip:
   
   ```
   pip install cryptography rsa
   ```

3. Launch the script with the following command:
   
   ```
   python server.py
   ```

4. The server will be set up to accept incoming connections from clients.

5. To shut down the server, type "exit" in the terminal where the server is running.

6. You can add users to the chat application by typing "update" in the server terminal and following the prompts to create new users.

### Important Note
- The script is also responsible for generating and managing encryption keys and user credentials. It is imperative to have a solid understanding of the code's functionality before deploying it in a production environment.

## `rsa.py` README

### Overview
The `rsa.py` script offers a set of functions for RSA encryption and key generation. These functions include generating both public and private key pairs, encrypting and decrypting data using RSA, and performing various mathematical operations associated with RSA.

### Functions
- `generate_key_pair(p, q)`: Generates an RSA key pair based on provided prime numbers.
- `encrypt(pk, plaintext)`: Encrypts plaintext using an RSA public key.
- `decrypt(pk, ciphertext)`: Decrypts ciphertext using an RSA private key.
- `is_prime(num)`: Verifies if a number is a prime number.
- Various mathematical helper functions for RSA operations.

### Usage
You can integrate the functions provided in this script into your projects for RSA encryption and decryption purposes.

Please keep in mind that RSA is a complex encryption algorithm, and it is vital to have a comprehensive understanding of how to use it securely and responsibly.

These README files serve as an introduction to the purpose and usage of each script. It is advisable to thoroughly review the code within each script for more in-depth information on their functionalities and any additional considerations or configurations that may be required for your specific use case.
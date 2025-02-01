# picoCTF-Solutions
Challenge: Repetitions

Flag: picoCTF{base64_n3st3d_dic0d!n8_d0wnl04d3d_4557ec3e}

Solution: The file contained a unique long base64 key. Using the online webshell, the key was decoded by repeatedly executing the base64 decode command (base64 -d filename). This process ultimately revealed the flag.
----------------------------------------------------------------------------------------
Challenge: Findme

Flag: picoCTF{proxies_all_the_way_3d9e3697}

Solution: After entering the specified login credentials, network recording in developer tools was monitored. Redirections were observed, and two base64 keys were discovered in the network data. Decoding these keys revealed the flag.
----------------------------------------------------------------------------------------
Challenge: Basic-mod2

Flag: picoCTF{1NV3R53LY_H4RD_DADAACAA}

Solution: Research on modular inverse was conducted to understand the concept. A Python script was written to map characters to numbers in the file, decrypting the message and revealing the flag.
----------------------------------------------------------------------------------------
Challenge: Fresh Java

Flag: picoCTF{700l1ng_r3qu1r3d_738cac89}

Solution: A Java compiler was used to read the full code properly. The .class file was downloaded and decompiled using Fernflower. This process revealed the flag.
----------------------------------------------------------------------------------------
Challenge: Permissions

Flag: picoCTF{uS1ng_v1m_3dit0r_f6ad392b}

Solution: Successful login to the main server was achieved using the provided credentials. Commands such as sudo and ls were used to search for the root file, eventually locating .flag.txt. This process was completed using the online webshell of picoCTF, revealing the flag.
----------------------------------------------------------------------------------------
Challenge: Irish-Name-Repo 1

Flag: picoCTF{s0m3_SQL_f8adf3fb}

Solution: Initial login attempts failed, prompting a search for credentials in the source code, which was unsuccessful. Information gathering about the website revealed it used an SQL database. SQL injection vulnerabilities were explored, and the SQL statement ' OR '1'='1 for both username and password allowed successful login, revealing the flag.
----------------------------------------------------------------------------------------

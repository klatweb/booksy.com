# booksy.com

<h2><b>TEST CASE 1</b></h2>


<b>[PL_ACCOUNT] Invalid account deletion instructions</b>
<br>
<br>
<b>Created:</b> <i>25/01/2023 by</i> <b>user1</b>
<br>
<br>
<b>Description:</b>
<br>
<i>User account cannot be deleted using the button as described in the FAQ section. A “delete account" button does not exist.</i>
<br>
<br>
<b>Preconditions:</b><i>
<br>1. User logged in.
<br>2. Polish language and region set.</i>
<br>
<br>
<b>Enviroment:</b>
<br>
<i>Google Chrome 109.0.5414.75</i>
<br>
<br>
<b>Priority:</b>
<br>
<i>Medium</i>
<br>
<br>
<b>Steps to reproduce:</b>
<br><i>1. Go to <url>https://booksy.com/pl-pl/faq#account</url>
<br>
2. Find section "Set-Up and Verification Codes".
<br>
3. Find section "Managing Your Booksy Account".</i>
<br>
4. Below, expand the tab "How can I delete my Booksy account?"
<br>
<a href="https://ibb.co/3T5WHRP"><img src="https://i.ibb.co/3T5WHRP/delete.png" alt="delete" border="0"></a>
<br>
<br>
<b>Result:</b>
<br><i>
A message appears: "By usunąć swoje konto w Booksy wejdź na swój profil a następnie kliknij na zakładkę Twoje dane. Tam znajdziesz przycisk Usuń moje konto."</i>
<br>
<br>
<b>Expected result:</b>
<br><i>
A message should appear: "Aby usunąć swoje konto na Booksy wyślij zgłoszenie na adres pomoc.pl@booksy.com z adresu e-mail zarejestrowanego na Booksy. Usuniemy Twoje konto."</i>
<br>
<br>
<br>
<br>
<br>
<h2><b>TEST CASE 2</b></h2>


<b>[PL_ACCOUNT] Logged out after region change</b>
<br>
<br>
<b>Created:</b> <i>25/01/2023 by</i> <b>user1</b>
<br>
<br>
<b>Description:</b>
<br>
<i>User gets logged out after trying to change region.</i>
<br>
<br>
<b>Preconditions:</b><i>
<br>1. User logged in.
<br>2. Polish language and region set.</i>
<br>
<br>
<b>Enviroment:</b>
<br>
<i>Google Chrome 109.0.5414.75</i>
<br>
<br>
<b>Priority:</b>
<br>
<i>High</i>
<br>
<br>
<b>Steps to reproduce:</b>
<br><i>1. Go to <url>https://booksy.com/pl-pl/</url>
<br>
2. Find section "Set-Up and Verification Codes".
<br>
3. Find section "Managing Your Booksy Account".</i>
<br>
4. Below, expand the tab "How can I delete my Booksy account?"
<br>
<a href="https://ibb.co/3T5WHRP"><img src="https://i.ibb.co/3T5WHRP/delete.png" alt="delete" border="0"></a>
<br>
<b>Result:</b>
<br><i>
A message appears: "By usunąć swoje konto w Booksy wejdź na swój profil a następnie kliknij na zakładkę Twoje dane. Tam znajdziesz przycisk Usuń moje konto."</i>
<br>
<br>
<b>Expected result:</b>
<br><i>
A message should appear: "Aby usunąć swoje konto na Booksy wyślij zgłoszenie na adres pomoc.pl@booksy.com z adresu e-mail zarejestrowanego na Booksy. Usuniemy Twoje konto."</i>

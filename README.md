>   Attention: ce repo est copié collé [ce repo](https://github.com/scienceetonnante/MCMC), des fichiers ont été ajoutés ou modifiés, mais le code n'est pas à un point stable et son exécution peut produire une erreur.
>
>   Certains fichiers ne devraient pas être suivis par Git, mais il n'est pas certain de pouvoir les reproduire, ils ont donc été conservés et doivent être supprimés lorsque ce repo est retravaillé.

# Decipher using Markov Chain Monte Carlo

Code used in my Youtube video : https://www.youtube.com/watch?v=z4tkHuWZbRA

Provided "as is" and without warranties of any kind :-)

I don't do any maintenance on it.

Run create_dictionnary.py once to create the dictionary.data file

Then run decipher_MCMC.py :
- set COUNT_BIGRAMS = True at least once to create the bigrams file (can then subsequently set to False)
- text to decipher should be in ciphered_text string (line 58)

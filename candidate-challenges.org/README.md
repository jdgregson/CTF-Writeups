# Candidate-Challenges.org
This was a fun little CTF I went through recently. It was engaging and technical, yet approachable for newcomers.

## Number of Flags
I've found 6 flags. I spoke with the creators of this CTF and they hinted that there _may_ be one more flag, bringing the total to 7. Maybe it has something to do with `C01` from the forensics flag.

## Challenges
#### 1. [Networking](networking-flag.md)
#### 2. [Forensics](forensics-flag.md)
#### 3. [Steganography](steganography-flag.md)
#### 4. [Cipher](cipher-flag.md)

## Finding the Challenges
Open [`style.css`](http://candidate-challenges.org/css/styles.css) and scroll to the bottom. You'll find a comment with the string `Li4vY2hhbGxlbmdlcy8`. Base64-decode that string and you'll get back `../challenges/`. Add that to the URL (`http://candidate-challenges.org/` + `../challenges/`) and submit and you'll be sent to the [`/challenges/`](http://candidate-challenges.org/challenges/) page.

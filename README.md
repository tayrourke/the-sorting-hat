# The Sorting

An unofficial Hogwarts sorting ceremony for Rosie’s eleventh birthday.

She answers twenty-seven questions. The Hat keeps its mouth shut until **3 September 2026**. On the day, the letter arrives, the Hat thinks aloud, and she finds out where she belongs.

This is a single web page. There is no server and no account. Her answers live in the browser on the device she used.

## The parent door

After she finishes, a tiny gold dot sits in the bottom-right corner. That is for you.

1. Tap it.
2. Type the keeper word (it starts as `keeper` — change this before you publish).
3. You will see her house, how close it was, and a nine-letter **sorting code**.
4. Copy the code and keep it somewhere she will not find.

The code is how you restore the result on another phone, tablet, or laptop. Without it, the sorting only exists on the device she used.

## Before you publish

Open `index.html` and edit the five lines at the top if you need to:

- `student` — the name on the letter
- `revealDate` — the morning the Hat is allowed to speak (`YYYY-MM-DD`)
- `address` — the envelope address
- `signedBy` — who signed the letter
- `keeperWord` — the word that opens the parent door

Anyone who can open the GitHub file can read that word. Pick something she will not guess.

## Put it on GitHub so she has a link

1. Create a new **public** GitHub repository (for example `the-sorting`).
2. Upload this folder, or from a terminal in this folder:

   ```bash
   git init -b main
   git add .
   git commit -m "The Sorting"
   git remote add origin https://github.com/YOUR-USERNAME/the-sorting.git
   git push -u origin main
   ```

3. In the repo: **Settings → Pages**.
4. Set **Source** to **Deploy from a branch**, branch `main`, folder `/ (root)`.
5. After a minute the site will be:

   `https://YOUR-USERNAME.github.io/the-sorting/`

That is the link she uses. Open it once yourself first.

If she has already been sorted on a phone, use the keeper door on **that** phone, copy the code, then on the new link tap **I have a sorting code** on the waiting screen (or use the parent door) and paste it.

## How the Hat decides

- Movement I (what she would do) and Movement II (what she would give up) count double.
- Movement III (what she is) is weighed lightly.
- The last question — if she already knows her house — is allowed as evidence, but it cannot outvote the rest of the ceremony.
- A true tie is broken by how often she leaned toward a house, then by the house the sorting code recorded, so a restore never flips the result.

## A note about names

Harry Potter, Hogwarts, and the four houses belong to their owners. This is a homemade birthday ceremony, not an official thing, and it is not for sale.

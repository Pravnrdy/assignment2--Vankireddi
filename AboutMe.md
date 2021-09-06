# Vankireddi Praveen Kumar Reddy
  My name is Praveen Reddy. I was a part of Indo-Us robot competetion held at IIT-Bombay and secured fourth place. I worked with Tech mahindra, India as a broad band tester for 13 months.<br> Later I joined amazon in level 3 position and got promoted to level 4 with in 17 months of experience which makes me one among the very few who cracked with in 2 years.<br><br>


  ![My picture](/praveen1.jpg?raw=true)

# FoodAndDrinks
  The Following Table illustrates the Best food and drinks available in different locations near me at the best price.<br> Please refer to this table and choose what you want.

   | Food/Drink | Location | Price |
   | ---------- | -------- | ----- |
   |   Coke     |   MCD    |  1$   |
   |   Burger   |  Tachos  |  1.5$ |
   |   Pizza    | Pizza hut|  8$   |
   |   Nuggets  | Taco Bell|  2$   |

---

# Pithy Quotes
> To live is the rarest thing in the world. Most people exist, that is all.
                                                                          -*Oscar Wilde*

> Everyone seems to have a clear idea of how other people should lead their lives, but none about his or her own.
                                                                           ― *Paulo Coelho,The Alchemist*

---

# String Processing 
> The thesis describes extensive studies on various algorithms for efficient string processing. Data available in/via computers are often of enormous size, and thus, it is significantly important and necessary to invent time- and space-efficient methods to process them. Most of such data are, in fact, stored and manipulated as strings. String matching is most fundamental in string processing, where the problem is to examine whether or not a pattern string p occurs in a text string w. There are two cases to consider; p is fixed and w is flexible, and vise versa. In the former case, it is adequate to employ the noble algorithm by Knuth, Morris, and Pratt that solves the problem in O(|w|) time using O(|p|) space. The thesis, on the other hand, considers the latter case. When w is fixed, it is natural, and ideal, to use a data structure that supports indices of w. Such a data structure is called an index structure. A linear-spaced index structure was first given by Weiner in 1973, named suffix trees. Suffix trees are regarded as a compaction of suffix tries that are a basic index structure requiring quadratic space. 
[Source](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.103.5899)

```
long long compute_hash(string const& s) {
    const int p = 31;
    const int m = 1e9 + 9;
    long long hash_value = 0;
    long long p_pow = 1;
    for (char c : s) {
        hash_value = (hash_value + (c - 'a' + 1) * p_pow) % m;
        p_pow = (p_pow * p) % m;
    }
    return hash_value;
}
```
[Source](https://cp-algorithms.com/string/string-hashing.html)






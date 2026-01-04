# 📌 BEFORE WEEK 1 (ONE-TIME SETUP — DO THIS FIRST)

### Tools (1–2 hours total)

### Folder structure

```
compression-project/
 ├─ playground/
 ├─ compressor/
 └─ notes/
```

You will write **notes**. Engineers write notes.

---

# 🧠 WEEKS 1–2: THINKING & PROBLEM SOLVING (FOUNDATION)

## 🎯 Goal

Stop “coding by instinct”. Start **thinking in steps**.

---

## WEEK 1 — Logic, Arrays, Strings

### Learn (in this order)

1. Variables, loops, conditionals (review if needed)
    
2. Arrays & strings
    
3. Writing logic _before_ code
    

### Resources

- **Read (primary):**
    
    - _Eloquent JavaScript_  
        👉 Chapters **1–4**  
        (Free, readable, not bloated)
        
- **Optional YouTube (ONLY if stuck):**
    
    - “JavaScript Problem Solving” – Fireship (short)
        
    - Avoid long beginner playlists
        

### Code (Daily)

Create `playground/week1.js`

Implement:

- Reverse a string
    
- Count characters in a string
    
- Find most frequent character
    
- Remove duplicates from array
    

### Rule

👉 **Write comments explaining your logic BEFORE code**

### Done when:

- You can explain each solution out loud
    
- You know what loop runs how many times
    

---

## WEEK 2 — Efficiency & Patterns

### Learn

1. What **Big-O** means (intuition only)
    
2. Hash maps (JS objects / Map)
    
3. Why some solutions are faster
    

### Resources

- **Read:**
    
    - Eloquent JavaScript — Chapter **4 (Data Structures)**
        
    - Short article: “Big O Notation Explained Simply”
        
- **Practice site (15–20 min/day):**
    
    - LeetCode → Easy only (arrays, strings)
        

### Code

Implement:

- Character frequency using Map
    
- Compare loop vs Map solution
    
- Run-Length Encoding (RLE):
    
    ```
    AAAABBBCC → A4B3C2
    ```
    

### Done when:

- You can say: _“This is O(n) because…”_
    

---

# 🧱 WEEKS 3–4: DATA, FILES & BINARY THINKING

## 🎯 Goal

Stop seeing files as “documents”. See **bytes**.

---

## WEEK 3 — Files & Buffers

### Learn

1. What a **byte** is
    
2. ASCII vs UTF-8
    
3. Reading files in Node.js
    

### Resources

- **Read:**
    
    - Node.js docs: `fs.readFile`, `Buffer`
        
- **Watch (important):**
    
    - “What is a Byte?” – Computerphile
        
    - “How Files Are Stored” – Computerphile
        

### Code

Create `playground/fileStats.js`

Program should:

- Read a file
    
- Count total bytes
    
- Count frequency of each byte (0–255)
    

### Done when:

- You understand why text ≠ bytes
    
- You can print binary data safely
    

---

## WEEK 4 — Binary & Representation

### Learn

1. Binary numbers
    
2. Bits vs bytes
    
3. Why compression is possible
    

### Resources

- **Read:**
    
    - Eloquent JS — Chapter **6 (Objects)** (skim)
        
- **Watch:**
    
    - “Binary & Data” – Ben Eater (essential)
        

### Code

- Convert numbers to binary manually
    
- Encode small strings into binary form
    

### Done when:

- You can explain how text becomes bits
    

---

# ⚙️ WEEKS 5–6: HUFFMAN COMPRESSION (CORE)

## 🎯 Goal

Build your **first real compressor**

---

## WEEK 5 — Trees & Huffman Theory

### Learn

1. Trees (basic)
    
2. Priority queues (conceptual)
    
3. Huffman coding idea
    

### Resources (IMPORTANT)

- **Read:**
    
    - “Huffman Coding Explained” (GeeksForGeeks)
        
- **Watch (must-watch):**
    
    - Computerphile — _Huffman Coding_
        

### Code

In `compressor/`:

- Build frequency table
    
- Build Huffman tree
    
- Generate codes
    

### Done when:

- You can draw the tree on paper
    

---

## WEEK 6 — Encode & Decode

### Learn

1. Encoding vs decoding
    
2. Storing metadata
    

### Code

- Encode file → compressed binary
    
- Decode compressed file → original
    
- Test with text files
    

### Done when:

🎉 You successfully compress and decompress a file

This is a **huge milestone**.

---

# 🧠 WEEKS 7–8: SYSTEMS THINKING

## 🎯 Goal

Understand _why_ code behaves the way it does

---

## WEEK 7 — Memory & Performance

### Learn

1. Stack vs heap (conceptual)
    
2. Garbage collection
    
3. Why C is fast (theory)
    

### Resources

- **Watch:**
    
    - “Stack vs Heap” – Computerphile
        
    - “Why C Is Fast” – Fireship
        

### Code

- Process files in chunks
    
- Compare speed vs whole-file reading
    

---

## WEEK 8 — Streaming & Buffers

### Learn

1. Streams
    
2. Buffering strategies
    

### Resources

- Node.js streams documentation
    
- Short stream tutorial (avoid long ones)
    

### Code

- Refactor compressor to stream data
    

### Done when:

- You stop loading whole files into memory
    

---

# 🚀 WEEKS 9–10: TOOLING & ENGINEERING

## WEEK 9 — CLI & Architecture

### Learn

1. CLI design
    
2. Clean modules
    

### Code

Create:

```
node compress input.txt output.huff
node decompress output.huff output.txt
```

---

## WEEK 10 — Benchmarking

### Learn

1. Measuring time
    
2. Compression ratio
    

### Code

- Measure speed
    
- Compare file sizes
    
- Improve bottlenecks
    

---

# 🧪 WEEKS 11–12: POLISH LIKE AN ENGINEER

## WEEK 11 — Edge Cases & Testing

- Large files
    
- Binary files
    
- Weird characters
    

## WEEK 12 — Documentation & Reflection

Write:

- README
    
- Architecture explanation
    
- What you’d improve in C/Rust
    

---

# 🔥 WHY THIS WILL WORK

By week 12:

- You won’t fear low-level concepts
    
- You’ll _understand_ compression
    
- You’ll be ready for computer engineering
    
- You’ll think like a builder, not a tutorial consumer
    

---

## NEXT MOVE

Tell me ONE of these and I’ll go even deeper:

1. **Break Week 1 into day-by-day tasks**
    
2. **Explain Huffman coding visually**
    
3. **Add a second hardware-leaning project**
    
4. **Turn this into a daily study schedule**
    

Pick one. We continue.
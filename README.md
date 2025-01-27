# Lyrics_to_ppt


This is a repo with works that involve worship experience in Church

### Step 1: Install Required Libraries
First, install the necessary Python libraries:
```bash
pip install python-pptx
```

---

### Step 2: Run the Script
1. Save the script to a file, e.g., `lyrics_to_ppt.py`.
2. Replace the `lyrics` variable with your desired song lyrics.
3. Run the script:
   ```bash
   python lyrics_to_ppt.py
   ```
4. The script will generate a PowerPoint file named `lyrics_presentation.pptx` in the same directory.

---

### Step 3: Customize (Optional)
- **Background Color**: Change the RGB value in `fill.fore_color.rgb` to customize the background.
- **Text Color**: Modify the `p.font.color.rgb` value to change the text color.
- **Font Size**: Adjust the `p.font.size` value to make the text larger or smaller.
- **Slide Layout**: You can experiment with different slide layouts by changing the index in `prs.slide_layouts[]`.

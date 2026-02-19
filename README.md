# 📓 Muthu Journal

A personal journal to track daily activities, learnings, ideas, and more. This repository provides a structured approach to journaling using Markdown files, making it easy to maintain, version control, and search through your entries.

## 🌟 Features

- **Daily Entries**: Track your daily activities, goals, and reflections
- **Template System**: Consistent structure for every entry
- **Organized Structure**: Year/Month folder organization for easy navigation
- **Version Control**: All entries are version-controlled with Git
- **Markdown Format**: Simple, readable, and portable format

## 📁 Folder Structure

```
Muthu-Journal/
├── README.md
├── templates/
│   └── daily-template.md          # Template for daily entries
└── YYYY/                          # Year folders
    └── MM/                        # Month folders
        └── YYYY-MM-DD.md          # Daily entries
```

## 📝 Template Format

Each daily entry follows a structured template with the following sections:

- **📅 Date**: The date of the entry
- **🎯 Goals for Today**: Checklist of daily goals (use `- [ ]` for unchecked, `- [x]` for completed)
- **📝 Activities**: Summary of what you did during the day
- **📚 Learnings**: New things you learned or discovered
- **💡 Ideas**: Creative ideas, inspirations, or thoughts
- **🙏 Gratitude**: Things you're grateful for
- **📊 Mood**: Emoji-based mood tracker
- **🔜 Tomorrow's Plan**: What you plan to do tomorrow

## 🚀 How to Use

### Creating a New Daily Entry

1. **Navigate to the correct folder** (or create it if it doesn't exist):
   ```bash
   mkdir -p YYYY/MM
   ```
   Replace `YYYY` with the year and `MM` with the month (e.g., `2026/02`)

2. **Copy the template**:
   ```bash
   cp templates/daily-template.md YYYY/MM/YYYY-MM-DD.md
   ```
   Replace the date with today's date (e.g., `2026/02/2026-02-19.md`)

3. **Fill in your entry**:
   - Update the `[DATE]` placeholder with the actual date
   - Check off goals as you complete them
   - Add your activities, learnings, ideas, and gratitude
   - Set your mood emoji (😊 😐 😢 😤 😴 🎉 etc.)
   - Plan for tomorrow

4. **Save and commit**:
   ```bash
   git add YYYY/MM/YYYY-MM-DD.md
   git commit -m "Journal entry for YYYY-MM-DD"
   git push
   ```

### Example Entry

See the sample entry at [`2026/02/2026-02-19.md`](2026/02/2026-02-19.md) for an example of a filled-in daily journal entry.

## 💡 Tips

- **Be consistent**: Try to write every day, even if it's just a few bullet points
- **Be honest**: This is your personal space—write freely
- **Review regularly**: Look back at past entries to track your progress
- **Customize**: Feel free to modify the template to suit your needs
- **Use emojis**: They make entries more visual and fun to read

## 🔧 Customization

You can customize the template by editing `templates/daily-template.md`. Add or remove sections based on what matters most to you.

## 📊 Benefits of Journaling

- Track your personal and professional growth
- Identify patterns in your mood and productivity
- Remember important learnings and ideas
- Practice gratitude and mindfulness
- Keep a searchable record of your life

---

Happy Journaling! 📝✨
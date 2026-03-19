# How to Add Resources to Your Worship Catalog

## Quick Start: Finding YouTube Video IDs

When you find a good YouTube video, the URL looks like:
```
https://www.youtube.com/watch?v=YqcEF7vNvXQ
```

The part after `v=` is the **Video ID**: `YqcEF7vNvXQ`

---

## Enhanced Resource Card Template

Copy this template and replace the ALL_CAPS parts:

```html
<div class="resource-card" onclick='openModal({
    category: "MINISTRY_OR_TEACHER_NAME",
    title: "VIDEO_TITLE",
    description: "One sentence describing what this teaches",
    videoId: "YOUTUBE_VIDEO_ID",
    scripture: {
        text: "The actual scripture text here",
        reference: "Book Chapter:Verse"
    },
    quote: {
        text: "A powerful quote from the video",
        author: "Who said it"
    },
    spiritualTruths: [
        "First spiritual truth or theological insight",
        "Second spiritual truth",
        "Third spiritual truth",
        "Fourth spiritual truth"
    ],
    practicalApplications: [
        "First practical way to apply this teaching",
        "Second practical application",
        "Third practical application",
        "Fourth practical application"
    ],
    takeaways: [
        "Quick summary point 1",
        "Quick summary point 2",
        "Quick summary point 3"
    ]
})'>
    <div class="card-image">
        <img src="https://img.youtube.com/vi/YOUTUBE_VIDEO_ID/maxresdefault.jpg" alt="VIDEO_TITLE">
        <div class="card-play-icon"></div>
    </div>
    <div class="card-content">
        <div class="card-category">MINISTRY_OR_TEACHER_NAME</div>
        <h3 class="card-title">VIDEO_TITLE</h3>
        <p class="card-description">One sentence describing what this teaches</p>
    </div>
</div>
```

---

## What Each Section Means:

### **Scripture** (Optional)
A key Bible verse that the video references or builds on
```javascript
scripture: {
    text: "God is spirit, and those who worship him must worship in spirit and truth.",
    reference: "John 4:24"
}
```

### **Quote** (Optional)
A memorable quote from the video
```javascript
quote: {
    text: "Worship is a way of gladly reflecting back to God the radiance of his worth.",
    author: "John Piper"
}
```

### **Spiritual Truths** (Optional)
Theological insights and deeper spiritual realities
- Focus on WHO GOD IS
- What the Bible teaches about worship
- Eternal truths that don't change
```javascript
spiritualTruths: [
    "Worship is the overflow of treasuring Christ above all things",
    "True worship requires both heart engagement and doctrinal accuracy"
]
```

### **Practical Applications** (Optional)
How to apply this in real life
- Action steps worship leaders can take
- Changes to implement on Sunday
- Personal habits to develop
```javascript
practicalApplications: [
    "Evaluate your personal worship: Does it reflect both passion and biblical truth?",
    "Choose songs that are both emotionally engaging and theologically sound"
]
```

### **Takeaways** (Optional)
Quick bullet points summarizing the video
```javascript
takeaways: [
    "Worship is treasuring Christ above all things",
    "Corporate worship prepares us for daily worship"
]
```

---

## Simple Version (Without Extra Details)

If you don't want all the details, you can use a simpler version:

```html
<div class="resource-card" onclick='openModal({
    category: "MINISTRY_NAME",
    title: "VIDEO_TITLE",
    description: "Brief description",
    videoId: "YOUTUBE_VIDEO_ID",
    takeaways: [
        "Key point 1",
        "Key point 2",
        "Key point 3"
    ]
})'>
    <div class="card-image">
        <img src="https://img.youtube.com/vi/YOUTUBE_VIDEO_ID/maxresdefault.jpg" alt="VIDEO_TITLE">
        <div class="card-play-icon"></div>
    </div>
    <div class="card-content">
        <div class="card-category">MINISTRY_NAME</div>
        <h3 class="card-title">VIDEO_TITLE</h3>
        <p class="card-description">Brief description</p>
    </div>
</div>
```

---

## Tips for Quality Content

### For Scripture References:
- Choose verses that are actually discussed in the video
- Use the actual Bible text, not a paraphrase
- Keep it to 1-2 verses max

### For Quotes:
- Pick the most memorable or powerful statement
- Make sure it's accurate (watch the video!)
- Keep it under 2 sentences

### For Spiritual Truths:
- Focus on timeless biblical principles
- Ask: "What does this reveal about God?"
- Avoid trendy or cultural observations

### For Practical Applications:
- Be specific and actionable
- Think about Monday, not just Sunday
- Consider different ministry contexts (small church, large church, etc.)

### For Takeaways:
- Keep them short (one sentence each)
- Focus on "what" not "how"
- 3-5 bullets max

---

## Where to Find Quality Resources

### Recommended YouTube Channels:
- **Desiring God** (John Piper)
- **The Gospel Coalition**
- **Worship Leader Magazine**
- **WorshipU**
- **Elevation Worship**
- **Bethel Music**
- **Hillsong Worship**
- **Jesus Culture**
- **Church of the Highlands**
- **9Marks**
- **Acts 29**

---

## Where to Paste the Code

1. Open `index.html`
2. Find the section you want (search for `id="biblical-foundation"` for example)
3. Find `<div class="resource-grid">`
4. Paste your new card code BEFORE the closing `</div>`
5. Save and test!

---

That's it! The enhanced content makes each video so much more valuable! 🎯

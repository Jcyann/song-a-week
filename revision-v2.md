# Song-a-Week - REVISION 2

## Current Version
- Random song generator
- Genre selection
- Basic UI

---

## NEW FEATURES NEEDED

### 1. Integrate with TuneVault
- Pull tunes from tunevault.org API or data
- Each tune links to TuneVault for learning

### 2. Smart Suggestions
- Assign tunes based on user's musical interests
- "What genres do you like?" → preference stored
- Algorithm suggests next tune based on preferences

### 3. 100 Most Popular Tunes Per Genre
- Background database of 100 popular tunes per genre:
  - Folk (100)
  - Blues (100)
  - Bluegrass (100)
  - Old Time (100)
  - Country (100)
  - Rock (100)

### 4. User Experience
- User CAN skip to next suggestion
- User CANNOT search or enter their own
- Forces engagement with suggested content

### 5. Funnel to TuneVault
- Each tune has "Learn this tune" → links to TuneVault
- "Book a lesson" button

---

## DATA STRUCTURE

```
Song {
  title
  artist
  genre
  difficulty (beginner/intermediate/advanced)
  tunevault_link
}
```

---

## TECHNICAL NOTES
- Built in Replit
- Can integrate TuneVault via their data
- Store preferences in LocalStorage

## MONETIZATION - ADD NOW
- Venmo tip jar: @Jason-Chinchen (add to every page!)
- Ko-fi: [TO ADD when Jason connects]

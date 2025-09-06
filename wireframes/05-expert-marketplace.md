# Expert Marketplace Wireframes

## Expert Discovery Page

```
┌─────────────────────────────────────────────────────────────────────────────┐
│ Header                                                                      │
│ ┌─────────┐                    ┌─────────┐ ┌─────────┐ ┌─────────┐        │
│ │  Logo   │                    │ Courses │ │ Experts │ │ Profile │        │
│ └─────────┘                    └─────────┘ └─────────┘ └─────────┘        │
└─────────────────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────────────────┐
│ Expert Discovery                                                            │
│                                                                             │
│ ┌─────────────────────────────────────────────────────────────────────┐   │
│ │ Search & Filters                                                    │   │
│ │                                                                     │   │
│ │ ┌─────────────────────────────────────────────────────────────┐     │   │
│ │ │ 🔍 Search: "Python programming"                             │     │   │
│ │ └─────────────────────────────────────────────────────────────┘     │   │
│ │                                                                     │   │
│ │ Filters:                                                           │   │
│ │ ┌─────────┐ ┌─────────┐ ┌─────────┐ ┌─────────┐                  │   │
│ │ │ Subject │ │ Rate    │ │ Rating  │ │ Time    │                  │   │
│ │ │ Python  │ │ $50-100 │ │ 4.5+    │ │ Today   │                  │   │
│ │ └─────────┘ └─────────┘ └─────────┘ └─────────┘                  │   │
│ └─────────────────────────────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────────────────┐
│ Available Experts                                                          │
│                                                                             │
│ ┌─────────────────────────────────────────────────────────────────────┐   │
│ │ Expert Card 1                                                       │   │
│ │ ┌─────────┐  Sarah Johnson - Python Expert                         │   │
│ │ │   👤    │  Senior Software Engineer at Google                    │   │
│ │ │ Avatar  │  ⭐⭐⭐⭐⭐ (4.9) • 150+ sessions • $75/hour            │   │
│ │ └─────────┘                                                         │   │
│ │                                                                     │   │
│ │ Specialties: Python, Django, Web Development, Data Science         │   │
│ │                                                                     │   │
│ │ "I love helping people learn Python! I have 8+ years of experience │   │
│ │  building web applications and can help you with any Python topic."│   │
│ │                                                                     │   │
│ │ Available: Today 2:00 PM, Tomorrow 10:00 AM                        │   │
│ │                                                                     │   │
│ │ ┌─────────────────┐    ┌─────────────────┐                        │   │
│ │ │  View Profile   │    │  Book Session   │                        │   │
│ │ └─────────────────┘    └─────────────────┘                        │   │
│ └─────────────────────────────────────────────────────────────────────┘   │
│                                                                             │
│ ┌─────────────────────────────────────────────────────────────────────┐   │
│ │ Expert Card 2                                                       │   │
│ │ ┌─────────┐  Michael Chen - Full Stack Developer                   │   │
│ │ │   👤    │  Tech Lead at Microsoft                                │   │
│ │ │ Avatar  │  ⭐⭐⭐⭐⭐ (4.8) • 200+ sessions • $90/hour            │   │
│ │ └─────────┘                                                         │   │
│ │                                                                     │   │
│ │ Specialties: Python, JavaScript, React, Node.js, AWS               │   │
│ │                                                                     │   │
│ │ "Passionate about teaching programming concepts in a clear,        │   │
│ │  practical way. I specialize in full-stack development and can     │   │
│ │  help you build real-world projects."                              │   │
│ │                                                                     │   │
│ │ Available: Today 4:00 PM, Wednesday 11:00 AM                       │   │
│ │                                                                     │   │
│ │ ┌─────────────────┐    ┌─────────────────┐                        │   │
│ │ │  View Profile   │    │  Book Session   │                        │   │
│ │ └─────────────────┘    └─────────────────┘                        │   │
│ └─────────────────────────────────────────────────────────────────────┘   │
│                                                                             │
│ ┌─────────────────────────────────────────────────────────────────────┐   │
│ │ Expert Card 3                                                       │   │
│ │ ┌─────────┐  Emily Rodriguez - Data Science Expert                 │   │
│ │ │   👤    │  Data Scientist at Netflix                             │   │
│ │ │ Avatar  │  ⭐⭐⭐⭐⭐ (4.9) • 120+ sessions • $85/hour            │   │
│ │ └─────────┘                                                         │   │
│ │                                                                     │   │
│ │ Specialties: Python, Machine Learning, Data Analysis, Pandas       │   │
│ │                                                                     │   │
│ │ "I help students master Python for data science and machine        │   │
│ │  learning. Let's build your data analysis skills together!"        │   │
│ │                                                                     │   │
│ │ Available: Tomorrow 3:00 PM, Thursday 2:00 PM                      │   │
│ │                                                                     │   │
│ │ ┌─────────────────┐    ┌─────────────────┐                        │   │
│ │ │  View Profile   │    │  Book Session   │                        │   │
│ │ └─────────────────┘    └─────────────────┘                        │   │
│ └─────────────────────────────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────────────────┐
│ Load More Experts                                                          │
│                                                                             │
│ ┌─────────────────────────────────────────────────────────────────────┐   │
│ │ ┌─────────────────┐                                                │   │
│ │ │  Load More      │                                                │   │
│ │ │  Experts        │                                                │   │
│ │ └─────────────────┘                                                │   │
│ └─────────────────────────────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────────────────────────────┘
```

## Expert Profile Page

```
┌─────────────────────────────────────────────────────────────────────────────┐
│ Expert Profile: Sarah Johnson                              ← Back to Search │
└─────────────────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────────────────┐
│ Expert Information                                                         │
│                                                                             │
│ ┌─────────────────────────────────────────────────────────────────────┐   │
│ │ ┌─────────┐  Sarah Johnson - Python Expert                         │   │
│ │ │   👤    │  Senior Software Engineer at Google                    │   │
│ │ │ Avatar  │  ⭐⭐⭐⭐⭐ (4.9) • 150+ sessions • $75/hour            │   │
│ │ └─────────┘                                                         │   │
│ │                                                                     │   │
│ │ ┌─────────────────┐    ┌─────────────────┐                        │   │
│ │ │  Book Session   │    │  Send Message   │                        │   │
│ │ └─────────────────┘    └─────────────────┘                        │   │
│ └─────────────────────────────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────────────────┐
│ About Sarah                                                                 │
│                                                                             │
│ ┌─────────────────────────────────────────────────────────────────────┐   │
│ │ Bio                                                                 │   │
│ │                                                                     │   │
│ │ "I'm a passionate Python developer with 8+ years of experience     │   │
│ │  building scalable web applications. I love teaching and helping   │   │
│ │  others learn Python in a practical, hands-on way.                 │   │
│ │                                                                     │   │
│ │ I specialize in Django, Flask, data analysis with Pandas, and      │   │
│ │  building RESTful APIs. Whether you're a beginner or looking to    │   │
│ │  advance your skills, I can help you achieve your goals."          │   │
│ │                                                                     │   │
│ │ Experience:                                                         │   │
│ │ • 8+ years Python development                                       │   │
│ │ • Senior Software Engineer at Google (3 years)                     │   │
│ │ • Previously at Amazon and Microsoft                               │   │
│ │ • Open source contributor to Django and Flask                      │   │
│ │                                                                     │   │
│ │ Education:                                                          │   │
│ │ • MS Computer Science, Stanford University                         │   │
│ │ • BS Computer Science, UC Berkeley                                 │   │
│ └─────────────────────────────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────────────────┐
│ Specialties & Availability                                                 │
│                                                                             │
│ ┌─────────────────────────────────────────────────────────────────────┐   │
│ │ Specialties                                                         │   │
│ │                                                                     │   │
│ │ ┌─────────┐ ┌─────────┐ ┌─────────┐ ┌─────────┐                  │   │
│ │ │ Python  │ │ Django  │ │ Flask   │ │ Pandas  │                  │   │
│ │ └─────────┘ └─────────┘ └─────────┘ └─────────┘                  │   │
│ │                                                                     │   │
│ │ ┌─────────┐ ┌─────────┐ ┌─────────┐ ┌─────────┐                  │   │
│ │ │ Web Dev │ │ APIs    │ │ Data    │ │ Testing │                  │   │
│ │ └─────────┘ └─────────┘ └─────────┘ └─────────┘                  │   │
│ │                                                                     │   │
│ │ Availability:                                                       │   │
│ │ • Monday-Friday: 2:00 PM - 8:00 PM PST                            │   │
│ │ • Saturday: 10:00 AM - 4:00 PM PST                                │   │
│ │ • Sunday: Closed                                                   │   │
│ │                                                                     │   │
│ │ Time Zone: Pacific Standard Time (PST)                             │   │
│ └─────────────────────────────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────────────────┐
│ Reviews & Ratings                                                          │
│                                                                             │
│ ┌─────────────────────────────────────────────────────────────────────┐   │
│ │ Overall Rating: 4.9/5 (150+ reviews)                               │   │
│ │                                                                     │   │
│ │ ⭐⭐⭐⭐⭐ (142) ⭐⭐⭐⭐ (8) ⭐⭐⭐ (0) ⭐⭐ (0) ⭐ (0)                │   │
│ │                                                                     │   │
│ │ Recent Reviews:                                                     │   │
│ │                                                                     │   │
│ │ "Sarah is an amazing teacher! She explained complex Python concepts │   │
│ │  in a way that was easy to understand. Highly recommended!"        │   │
│ │ - John D. • 5 stars • 2 days ago                                   │   │
│ │                                                                     │   │
│ │ "Great session! Sarah helped me debug my Django project and taught  │   │
│ │  me some best practices I didn't know about."                      │   │
│ │ - Maria S. • 5 stars • 1 week ago                                  │   │
│ │                                                                     │   │
│ │ "Very patient and knowledgeable. Sarah made learning Python fun     │   │
│ │  and engaging. I'll definitely book more sessions!"                │   │
│ │ - Alex K. • 5 stars • 2 weeks ago                                  │   │
│ │                                                                     │   │
│ │ ┌─────────────────┐                                                │   │
│ │ │  View All       │                                                │   │
│ │ │  Reviews        │                                                │   │
│ │ └─────────────────┘                                                │   │
│ └─────────────────────────────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────────────────────────────┘
```

## Booking Flow

```
┌─────────────────────────────────────────────────────────────────────────────┐
│ Book Session with Sarah Johnson                            ✕ Close          │
└─────────────────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────────────────┐
│ Step 1: Select Date & Time                                                 │
│                                                                             │
│ ┌─────────────────────────────────────────────────────────────────────┐   │
│ │ Calendar View                                                      │   │
│ │                                                                     │   │
│ │ ┌─────────────────────────────────────────────────────────────┐     │   │
│ │ │ January 2024                                              │     │   │
│ │ │                                                             │     │   │
│ │ │  S  M  T  W  T  F  S                                       │     │   │
│ │ │     1  2  3  4  5  6                                       │     │   │
│ │ │  7  8  9 10 11 12 13                                       │     │   │
│ │ │ 14 15 16 17 18 19 20                                       │     │   │
│ │ │ 21 22 23 24 25 26 27                                       │     │   │
│ │ │ 28 29 30 31                                                 │     │   │
│ │ └─────────────────────────────────────────────────────────────┘     │   │
│ │                                                                     │   │
│ │ Available Times for January 15, 2024:                              │   │
│ │ ┌─────────┐ ┌─────────┐ ┌─────────┐ ┌─────────┐                  │   │
│ │ │ 2:00 PM │ │ 3:00 PM │ │ 4:00 PM │ │ 5:00 PM │                  │   │
│ │ └─────────┘ └─────────┘ └─────────┘ └─────────┘                  │   │
│ │                                                                     │   │
│ │ ┌─────────┐ ┌─────────┐ ┌─────────┐ ┌─────────┐                  │   │
│ │ │ 6:00 PM │ │ 7:00 PM │ │         │ │         │                  │   │
│ │ └─────────┘ └─────────┘ └─────────┘ └─────────┘                  │   │
│ └─────────────────────────────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────────────────┐
│ Step 2: Session Details                                                    │
│                                                                             │
│ ┌─────────────────────────────────────────────────────────────────────┐   │
│ │ Session Configuration                                              │   │
│ │                                                                     │   │
│ │ Duration:                                                           │   │
│ │ ┌─────────────────────────────────────────────────────────────┐     │   │
│ │ │ 1 hour (recommended)                                       │     │   │
│ │ └─────────────────────────────────────────────────────────────┘     │   │
│ │                                                                     │   │
│ │ Session Type:                                                       │   │
│ │ ┌─────────────────────────────────────────────────────────────┐     │   │
│ │ │ One-on-one session                                         │     │   │
│ │ └─────────────────────────────────────────────────────────────┘     │   │
│ │                                                                     │   │
│ │ What would you like to focus on?                                   │   │
│ │ ┌─────────────────────────────────────────────────────────────┐     │   │
│ │ │ I need help with Django models and database relationships  │     │   │
│ │ └─────────────────────────────────────────────────────────────┘     │   │
│ │                                                                     │   │
│ │ Special requests or questions:                                      │   │
│ │ ┌─────────────────────────────────────────────────────────────┐     │   │
│ │ │ Please bring examples of common model relationships        │     │   │
│ │ └─────────────────────────────────────────────────────────────┘     │   │
│ └─────────────────────────────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────────────────┐
│ Step 3: Payment & Confirmation                                             │
│                                                                             │
│ ┌─────────────────────────────────────────────────────────────────────┐   │
│ │ Session Summary                                                     │   │
│ │                                                                     │   │
│ │ Expert: Sarah Johnson                                               │   │
│ │ Date: January 15, 2024                                             │   │
│ │ Time: 2:00 PM - 3:00 PM PST                                        │   │
│ │ Duration: 1 hour                                                    │   │
│ │ Rate: $75/hour                                                      │   │
│ │                                                                     │   │
│ │ Total: $75.00                                                       │   │
│ │                                                                     │   │
│ │ Payment Method:                                                     │   │
│ │ ┌─────────────────────────────────────────────────────────────┐     │   │
│ │ │ 💳 •••• 1234 (Expires 12/25)                              │     │   │
│ │ └─────────────────────────────────────────────────────────────┘     │   │
│ │                                                                     │   │
│ │ ┌─────────────────┐    ┌─────────────────┐                        │   │
│ │ │  Back           │    │  Book Session   │                        │   │
│ │ └─────────────────┘    └─────────────────┘                        │   │
│ └─────────────────────────────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────────────────────────────┘
```

## Mobile Expert Marketplace

```
┌─────────────────────────┐
│ Header                  │
│ ┌─────┐        ☰ Menu   │
│ │Logo │                 │
│ └─────┘                 │
└─────────────────────────┘

┌─────────────────────────┐
│ Expert Discovery        │
│                         │
│ 🔍 Search: "Python"     │
│                         │
│ Filters:                │
│ ┌─────┐ ┌─────┐ ┌─────┐ │
│ │Subj │ │Rate │ │Rate │ │
│ │Python│ │$50- │ │4.5+ │ │
│ └─────┘ └─────┘ └─────┘ │
└─────────────────────────┘

┌─────────────────────────┐
│ Expert Card             │
│                         │
│ 👤 Sarah Johnson        │
│ Python Expert           │
│ ⭐⭐⭐⭐⭐ (4.9)          │
│ $75/hour                │
│                         │
│ Specialties: Python,    │
│ Django, Web Dev         │
│                         │
│ Available: Today 2:00   │
│ PM, Tomorrow 10:00 AM   │
│                         │
│ ┌─────────────────┐     │
│ │  Book Session   │     │
│ └─────────────────┘     │
└─────────────────────────┘

┌─────────────────────────┐
│ Expert Card             │
│                         │
│ 👤 Michael Chen         │
│ Full Stack Developer    │
│ ⭐⭐⭐⭐⭐ (4.8)          │
│ $90/hour                │
│                         │
│ Specialties: Python,    │
│ JavaScript, React       │
│                         │
│ Available: Today 4:00   │
│ PM, Wed 11:00 AM        │
│                         │
│ ┌─────────────────┐     │
│ │  Book Session   │     │
│ └─────────────────┘     │
└─────────────────────────┘

┌─────────────────────────┐
│ Load More Experts       │
│                         │
│ ┌─────────────────┐     │
│ │  Load More      │     │
│ └─────────────────┘     │
└─────────────────────────┘
```

## Key Design Elements

### Expert Discovery
- **Search functionality** with autocomplete
- **Filter options** for subject, rate, rating, availability
- **Expert cards** with key information
- **Clear CTAs** for booking sessions

### Expert Profiles
- **Comprehensive information** about the expert
- **Specialties and experience** clearly displayed
- **Availability calendar** integration
- **Reviews and ratings** from previous sessions

### Booking Flow
- **Step-by-step process** for session booking
- **Calendar integration** for availability
- **Session customization** options
- **Payment processing** with confirmation

### Mobile Optimization
- **Stacked layout** for mobile screens
- **Touch-friendly** buttons and controls
- **Swipe gestures** for navigation
- **Simplified** booking process

### Interactive Features
- **Real-time availability** updates
- **Instant booking** confirmation
- **Payment processing** integration
- **Calendar synchronization**

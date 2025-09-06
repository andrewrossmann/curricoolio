# Dashboard Wireframe

## Main Dashboard Layout

```
┌─────────────────────────────────────────────────────────────────────────────┐
│ Header                                                                      │
│ ┌─────────┐                    ┌─────────┐ ┌─────────┐ ┌─────────┐        │
│ │  Logo   │                    │ Courses │ │ Progress│ │ Profile │        │
│ └─────────┘                    └─────────┘ └─────────┘ └─────────┘        │
└─────────────────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────────────────┐
│ Welcome Back, Andrew!                                                      │
│                                                                             │
│ ┌─────────────────────────────────────────────────────────────────────┐   │
│ │ Current Course: Python Web Development                             │   │
│ │                                                                     │   │
│ │ ┌─────────────────────────────────────────────────────────────┐     │   │
│ │ │ Progress: 8 of 20 sessions completed (40%)                 │     │   │
│ │ │ ████████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ │     │   │
│ │ └─────────────────────────────────────────────────────────────┘     │   │
│ │                                                                     │   │
│ │ Next Session: Session 9 - Django Models & Databases                │   │
│ │ Scheduled: Today at 2:00 PM                                        │   │
│ │                                                                     │   │
│ │ ┌─────────────────┐    ┌─────────────────┐                        │   │
│ │ │  Start Session  │    │  View Schedule  │                        │   │
│ │ └─────────────────┘    └─────────────────┘                        │   │
│ └─────────────────────────────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────────────────┐
│ Quick Stats                                                                 │
│                                                                             │
│ ┌─────────────┐  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐      │
│ │ Total Time  │  │ Sessions    │  │ Current     │  │ Achievements│      │
│ │ Spent       │  │ Completed   │  │ Streak      │  │ Unlocked    │      │
│ │             │  │             │  │             │  │             │      │
│ │ 12 hours    │  │ 8 of 20     │  │ 5 days      │  │ 3 badges    │      │
│ │             │  │             │  │             │  │             │      │
│ │ ┌─────────┐ │  │ ┌─────────┐ │  │ ┌─────────┐ │  │ ┌─────────┐ │      │
│ │ │ 📊 12h  │ │  │ │ ✅ 8/20 │ │  │ │ 🔥 5    │ │  │ │ 🏆 3    │ │      │
│ │ └─────────┘ │  │ └─────────┘ │  │ └─────────┘ │  │ └─────────┘ │      │
│ └─────────────┘  └─────────────┘  └─────────────┘  └─────────────┘      │
└─────────────────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────────────────┐
│ Upcoming Sessions                                                          │
│                                                                             │
│ ┌─────────────────────────────────────────────────────────────────────┐   │
│ │ Today's Schedule                                                   │   │
│ │                                                                     │   │
│ │ ┌─────────────────────────────────────────────────────────────┐     │   │
│ │ │ 2:00 PM - Session 9: Django Models & Databases             │     │   │
│ │ │ Duration: 1 hour | Status: Scheduled                        │     │   │
│ │ └─────────────────────────────────────────────────────────────┘     │   │
│ │                                                                     │   │
│ │ ┌─────────────────────────────────────────────────────────────┐     │   │
│ │ │ Tomorrow - Session 10: Django Views & Templates             │     │   │
│ │ │ Duration: 1 hour | Status: Scheduled                        │     │   │
│ │ └─────────────────────────────────────────────────────────────┘     │   │
│ │                                                                     │   │
│ │ ┌─────────────────────────────────────────────────────────────┐     │   │
│ │ │ Wednesday - Session 11: Django Forms & User Input           │     │   │
│ │ │ Duration: 1 hour | Status: Scheduled                        │     │   │
│ │ └─────────────────────────────────────────────────────────────┘     │   │
│ └─────────────────────────────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────────────────┐
│ Recent Activity                                                             │
│                                                                             │
│ ┌─────────────────────────────────────────────────────────────────────┐   │
│ │ Activity Feed                                                       │   │
│ │                                                                     │   │
│ │ ✅ Completed Session 8: Python Functions & Classes                  │   │
│ │   2 hours ago                                                       │   │
│ │                                                                     │   │
│ │ 🏆 Earned "Code Master" badge                                       │   │
│ │   2 hours ago                                                       │   │
│ │                                                                     │   │
│ │ 📝 Added notes to Session 7: Object-Oriented Programming            │   │
│ │   Yesterday                                                          │   │
│ │                                                                     │   │
│ │ ✅ Completed Session 7: Object-Oriented Programming                 │   │
│ │   Yesterday                                                          │   │
│ │                                                                     │   │
│ │ ┌─────────────────┐                                                │   │
│ │ │  View All       │                                                │   │
│ │ │  Activity       │                                                │   │
│ │ └─────────────────┘                                                │   │
│ └─────────────────────────────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────────────────────────────┘
```

## Mobile Dashboard Layout

```
┌─────────────────────────┐
│ Header                  │
│ ┌─────┐        ☰ Menu   │
│ │Logo │                 │
│ └─────┘                 │
└─────────────────────────┘

┌─────────────────────────┐
│ Welcome Back, Andrew!   │
│                         │
│ Current Course:         │
│ Python Web Development  │
│                         │
│ Progress: 8/20 (40%)    │
│ ████████████░░░░░░░░░░  │
│                         │
│ Next Session:           │
│ Session 9 - Django      │
│ Models & Databases      │
│ Today at 2:00 PM        │
│                         │
│ ┌─────────────────┐     │
│ │  Start Session  │     │
│ └─────────────────┘     │
└─────────────────────────┘

┌─────────────────────────┐
│ Quick Stats             │
│                         │
│ ┌─────┐ ┌─────┐ ┌─────┐ │
│ │ 📊  │ │ ✅  │ │ 🔥  │ │
│ │ 12h │ │ 8/20│ │ 5   │ │
│ └─────┘ └─────┘ └─────┘ │
│                         │
│ ┌─────┐ ┌─────┐ ┌─────┐ │
│ │ 🏆  │ │     │ │     │ │
│ │ 3   │ │     │ │     │ │
│ └─────┘ └─────┘ └─────┘ │
└─────────────────────────┘

┌─────────────────────────┐
│ Today's Schedule        │
│                         │
│ 2:00 PM - Session 9     │
│ Django Models &         │
│ Databases               │
│ 1 hour | Scheduled      │
│                         │
│ ┌─────────────────┐     │
│ │  View Schedule  │     │
│ └─────────────────┘     │
└─────────────────────────┘

┌─────────────────────────┐
│ Recent Activity         │
│                         │
│ ✅ Completed Session 8  │
│ Python Functions &      │
│ Classes                 │
│ 2 hours ago             │
│                         │
│ 🏆 Earned "Code Master" │
│ badge                   │
│ 2 hours ago             │
│                         │
│ ┌─────────────────┐     │
│ │  View All       │     │
│ │  Activity       │     │
│ └─────────────────┘     │
└─────────────────────────┘
```

## Course Overview Modal

```
┌─────────────────────────────────────────────────────────────────────────────┐
│ Course Overview: Python Web Development                    ✕ Close          │
└─────────────────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────────────────┐
│ Course Details                                                             │
│                                                                             │
│ ┌─────────────────────────────────────────────────────────────────────┐   │
│ │ Course Information                                                  │   │
│ │                                                                     │   │
│ │ Subject: Python Web Development                                    │   │
│ │ Total Sessions: 20                                                 │   │
│ │ Duration: 1 hour per session                                       │   │
│ │ Schedule: Monday-Friday, 2:00 PM                                   │   │
│ │ Start Date: January 15, 2024                                       │   │
│ │ End Date: February 9, 2024                                         │   │
│ │                                                                     │   │
│ │ Learning Objectives:                                                │   │
│ │ • Build complete web applications with Python and Django           │   │
│ │ • Understand database design and management                         │   │
│ │ • Implement user authentication and authorization                   │   │
│ │ • Deploy applications to production                                │   │
│ │                                                                     │   │
│ │ ┌─────────────────┐    ┌─────────────────┐                        │   │
│ │ │  Edit Course    │    │  View Sessions  │                        │   │
│ │ └─────────────────┘    └─────────────────┘                        │   │
│ └─────────────────────────────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────────────────────────────┘
```

## Key Design Elements

### Progress Visualization
- **Progress bars** with percentage completion
- **Visual indicators** for current status
- **Color coding** for different states (completed, current, upcoming)

### Quick Actions
- **Primary CTA** for starting next session
- **Secondary actions** for viewing details
- **Easy navigation** to different sections

### Information Hierarchy
- **Most important info** at the top (current course, next session)
- **Supporting details** below (stats, schedule, activity)
- **Clear visual separation** between sections

### Mobile Optimization
- **Stacked layout** for mobile screens
- **Touch-friendly** buttons and controls
- **Swipe gestures** for navigation
- **Collapsible sections** to save space

### Interactive Elements
- **Hover states** on clickable elements
- **Loading states** for async operations
- **Real-time updates** for progress and activity
- **Smooth animations** for state changes

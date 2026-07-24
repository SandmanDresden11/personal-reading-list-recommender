# Personal Reading List Recommender

A Claude Artifact that tracks reading progress and recommends what
to read next based on completed books, ratings, written reactions,
reading goals, and current preferences.

## Features

- Personal reading-list tracker
- Five reading-status categories
- Ratings and reading notes
- Genre and progress filters
- Personalized next-book recommendations
- Live web research and source citations
- Persistent reading history
- Saved recommendation history
- Spreadsheet export

## Recommendation Process

The Artifact considers:

- completed and abandoned books;
- numerical ratings;
- favorite and disliked qualities;
- preferred pacing and complexity;
- reading mood;
- available time;
- desired book length;
- current reading goals.

## Testing

The project was tested by:

1. Choosing a book from an existing reading list
2. Finding a new nonfiction book under 400 pages
3. Recommending something different while respecting prior dislikes

## Revision

The initial version relied too heavily on genre and ratings.
It was revised to analyze written reactions, pacing, complexity,
tone, and reasons for abandoning books.

## Known Limitation

Recommendation quality depends on the amount and accuracy of the
reading-history information entered by the user.

## Published Artifact

(https://claude.ai/public/artifacts/29dd8150-abf0-4b99-ac42-752a027b7001)

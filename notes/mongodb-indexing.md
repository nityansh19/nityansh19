# MongoDB Indexing Notes

- Add indexes for fields used frequently in filters and sorting.
- Avoid creating indexes without measuring query patterns.
- Compound index order matters.
- Use explain plans when a query becomes slow.
- Remember that indexes improve reads but add write and storage cost.

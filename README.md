
# Gen AI Analytics Dashboard

A React-based dashboard prototype for a Gen AI Analytics tool that demonstrates query interaction and result visualization.

## Project Info

This dashboard prototype showcases:

- Natural language query input with AI-powered suggestions
- Query history tracking
- Dynamic data visualization based on query content
- Responsive design for all device sizes

## Tech Stack

- **Frontend:** React.js
- **State Management:** Redux Toolkit
- **Routing:** React Router
- **UI Components:** shadcn/ui
- **Styling:** Tailwind CSS
- **Data Visualization:** Recharts

## Features

### Query Input
- Natural language query input with suggestions
- AI-powered query processing simulation
- Dynamic suggestions based on input

### Data Visualization
- Multiple chart types (bar, line, area, pie)
- Responsive visualizations
- AI-generated insights for each result

### Query History
- Track recent queries
- Rerun previous queries with one click
- Timestamp for each query

## Development

### Running Locally

1. Clone the repository
2. Install dependencies: `npm install`
3. Start the development server: `npm run dev`
4. Open your browser at: `http://localhost:8080`

## Project Structure

```
src/
├── components/        # UI components
├── hooks/             # Custom React hooks
├── pages/             # Page components
├── store/             # Redux store and slices
└── index.css          # Global styles
```

## Design Inspiration

This project draws inspiration from modern analytics dashboards with a focus on:
- Clean, minimalist UI
- Clear data visualization
- Intuitive user experience
- Accessible design patterns

## Future Enhancements

- User authentication
- Custom dashboard creation
- Advanced filtering options
- Export functionality
- Real-time data updates

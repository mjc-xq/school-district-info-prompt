# School District Information Application Prompt

Generate a full-stack web application that retrieves and displays school district information using the Perplexity API. The application should have both backend and frontend components with the following specifications:

## Core Features Required:
1. User input form for school district name and state
2. Integration with Perplexity API for data retrieval
3. Display of comprehensive school district information
4. Clean, responsive user interface

## Backend Requirements:

### Technology Stack:
- Node.js with Express.js
- Perplexity API integration
- Error handling and input validation
- Rate limiting for API calls
- Caching system for frequently requested districts

### API Endpoints:
```typescript
// Create the following REST endpoints:
POST /api/district-info
  - Accepts: { districtName: string, state: string }
  - Returns: {
      districtInfo: {
        name: string,
        boardMembers: Array<{
          name: string,
          email: string,
          position?: string
        }>,
        upcomingMeetings: Array<{
          date: string,
          time: string,
          location: string,
          topics: string[]
        }>
      }
    }
```

### Perplexity API Integration:
1. Implement function to construct search queries for:
   - School board member information
   - Upcoming meeting schedules
   - Meeting agenda topics
2. Parse and structure the Perplexity API responses
3. Implement error handling for API failures
4. Add request caching to minimize API calls

## Frontend Requirements:

### Technology Stack:
- React.js with TypeScript
- Tailwind CSS for styling
- React Query for data fetching
- React Hook Form for form handling

### Components Structure:
```typescript
// Create the following components:
1. SearchForm
   - Input fields for district name and state
   - Form validation
   - Loading state handling

2. DistrictInfo
   - Display district name and general info
   - Organized layout for board member details

3. BoardMembers
   - List of board members with contact info
   - Grid or table layout
   - Email click-to-copy functionality

4. MeetingSchedule
   - Calendar view of upcoming meetings
   - Expandable meeting details
   - Topic list for each meeting

5. ErrorBoundary
   - Handle and display errors gracefully
   - Provide retry functionality
```

### UI/UX Requirements:
1. Responsive design for mobile and desktop
2. Loading states and animations
3. Error messages for failed searches
4. Empty state handling
5. Accessibility compliance (WCAG 2.1)

### Styling Guidelines:
```css
/* Color Scheme */
--primary: #1e40af;  // Deep blue
--secondary: #60a5fa;  // Light blue
--accent: #f59e0b;  // Amber
--background: #f3f4f6;  // Light gray
--text: #1f2937;  // Dark gray

/* Typography */
font-family: 'Inter', sans-serif;
headings: font-weight: 700
body: font-weight: 400
```

## Error Handling:
1. Input validation errors
2. API request failures
3. No results found
4. Rate limit exceeded
5. Network connectivity issues

## Performance Considerations:
1. Implement client-side caching
2. Optimize API requests
3. Lazy loading for components
4. Image optimization
5. Minimize bundle size

## Security Requirements:
1. Input sanitization
2. API key protection
3. Rate limiting
4. CORS configuration
5. XSS prevention

## Testing Requirements:
1. Unit tests for components
2. Integration tests for API calls
3. E2E tests for critical paths
4. Accessibility testing
5. Performance testing

## Deployment Considerations:
1. Environment configuration
2. API key management
3. Build optimization
4. Error logging
5. Analytics integration

## Example Usage:
```javascript
// Example of how to use the application:
1. User enters "Springfield School District" and "Illinois"
2. System queries Perplexity API with structured prompts
3. Backend processes and structures the data
4. Frontend displays organized information
5. User can interact with meeting schedule and contact info
```

## Additional Features:
1. Export data to PDF/CSV
2. Email notifications for new meetings
3. Calendar integration
4. Social media links
5. Historical meeting archives

## Documentation Requirements:
1. API documentation
2. Setup instructions
3. Environment configuration
4. Deployment guide
5. Troubleshooting guide

Remember to:
- Follow React best practices
- Implement proper TypeScript typing
- Use modern ES6+ features
- Follow accessibility guidelines
- Implement proper error handling
- Add comprehensive documentation
- Include test coverage
- Optimize for performance
- Consider scalability
- Implement security best practices
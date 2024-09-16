
Example Commit Messages
Initial Setup
Header: Initial project setup with React and Node.js
Body:
markdown
Copy code
- Cloned the Razorpay React demo repository.
- Set up the frontend React application.
- Configured the backend Node.js server.
- Added sample `.env` files for configuration.
Frontend Changes
Header: Added Razorpay checkout script to frontend
Body:
markdown
Copy code
- Included Razorpay checkout script in public/index.html.
- Updated frontend `.env` file instructions for API keys.
- Fixed missing Razorpay script reference in React component.
Backend Changes
Header: Configured backend server for Razorpay API
Body:
markdown
Copy code
- Set up Node.js server with Razorpay SDK.
- Added endpoints for creating orders and processing refunds.
- Updated backend `.env` file instructions for API keys and secrets.
Fixes
Header: Fixed bug in Razorpay order creation
Body:
vbnet
Copy code
- Corrected issue with order creation logic in backend.
- Improved error handling for API requests.
Refactoring
Header: Refactored payment handling in frontend
Body:
diff
Copy code
- Simplified payment handling logic in React components.
- Moved payment configuration to a separate file.
- Improved user interface for payment status feedback.
Example Commit Messages for Specific Changes
Added Razorpay checkout integration:

diff
Copy code
Added Razorpay checkout integration to the React frontend

- Included the Razorpay checkout script in public/index.html.
- Implemented checkout button functionality in Payment component.
- Updated frontend documentation with setup instructions.
Updated backend to support refunds:

diff
Copy code
Implemented refund functionality in backend server

- Added endpoint for processing refunds.
- Integrated refund handling with Razorpay SDK.
- Updated backend configuration to include refund API key and secret.
Fixed typo in .env sample file:

diff
Copy code
Corrected typo in sample.env file

- Fixed placeholder values in sample.env.
- Updated README with correct environment variable names.
Tips for Writing Good Commit Messages
Be Descriptive: Explain the purpose and impact of your changes.
Use Imperative Mood: Write commit messages as if you are giving commands (e.g., "Add", "Fix", "Update").
Keep It Concise: Summarize the changes in the header and provide detailed explanations in the body if needed.

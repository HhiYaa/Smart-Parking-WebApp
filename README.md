# Smart-Parking-WebApp
Smart Parking WebApp
 * Smart Parking Web App
   
 * A full-stack web app allowing users to search, view, and book real-time parking spots.
   
 * Features:
 * - React frontend: Responsive UI, Google Maps integration
 * - Node.js backend: RESTful APIs for data and booking management
 * - AWS: S3 (hosting), Lambda (serverless backend), DynamoDB (data)
 * - Google Maps API: Displays geolocation and available spots
 * - Authentication and payment flows (extendable)
 *
 * Run locally:
 * - Frontend: npm start (on port 3000)
 * - Backend: node index.js (on port 5000)
 * - Set up proxy in package.json for API calls
 */

 // 1. Frontend: Deploy to AWS S3 bucket as a static website.
// 2. Backend: Use AWS Lambda + API Gateway (convert Express routes to Lambda handlers using serverless-http).
// 3. Database: DynamoDB tables for users, parking spots, and reservations.


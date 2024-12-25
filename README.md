**NasaAstroApp-ReactJs**


![1](https://github.com/user-attachments/assets/0b064614-4a7c-4560-8440-b10b525af2b1)
![2](https://github.com/user-attachments/assets/4795ff9f-9c28-43fb-a9dd-50bee8cf99f1)

# NASA Picture of the Day App

This app fetches and displays NASA's Astronomy Picture of the Day (APOD).

## Challenges & Solutions:

- **Fetching Data**:  
  Used `fetch()` inside `useEffect` to get data from the NASA API.

- **Storing Data**:  
  Stored the API response in `useState` and passed it to components as props.

- **Modal Toggle**:  
  Used `handleToggleModal` and `useState` to show/hide the sidebar.

- **Environment Variables**:  
  Stored the API key in a `.env` file for security.

- **Component Structure**:  
  Broke UI into reusable components (`Main`, `SideBar`, `Footer`).

## Setup

1. Clone this repository:

   ```bash
   git clone <repository-url>
2. Install dependencies:

   ```bash
    npm install
3. Create a .env file in the root directory with the following line (replace with your actual NASA API key):

   ```bash
       VITE_NASA_API_KEY=your_api_key_here
4. Run the app:

   ```bash
      npm run dev
- **API Details**

    API URL: https://api.nasa.gov/planetary/apod

    API Key: Sign up on the NASA API page to obtain an API key.


# takeuforward Assignment


## Test credentials for Admin

 **Username :**
   ```bash
   admin2
   ```

 **Password :**
   ```bash
   adminpassword
   ```

<br>


## Test credentials for User

 **Username :**
   ```bash
   vvlegend33
   ```

 **Password :**
   ```bash
   userpassword
   ```

<br><br>

## 🚀 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/vighnesh-7/takeuforward
   cd takeuforward
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Create a `.env` file:**
   Copy the `.env.sample` file to `.env` and fill in the required values:
   ```bash
   cp .env.sample .env
   ```

4. **Run the application:**
   ```bash
   npm run dev
   ```

5. **Open your browser:**
   Visit [`http://localhost:3000/`](http://localhost:3000/)


## 🌟 Features

- **User Authentication:** Secure signup with Google OAuth and manual signin.
- **Admin Dashboard:** Create Flash cards or use Ai generated Flashcard generation with all CRUD operations.
- **Personalization:** Dark/Light mode and profile management

## 📜 Environment Variables

| Variable              | Description                                       
|-----------------------|-------------------------------------
| `DATABASE_URL`        | PostgreSQL connection string                     
| `NEXTAUTH_GOOGLE_ID`  | Google OAuth Client ID                            
| `NEXTAUTH_GOOGLE_SECRET` | Google OAuth Client Secret                     
| `NEXTAUTH_SECRET`     | Secret for NextAuth.js                           
| `NEXTAUTH_URL`        | Base URL for NextAuth.js                          
| `NEXTAUTH_URL_INTERNAL` | Internal URL for NextAuth.js                   
| `GEMINI_API_KEY`      | API key for Gemini                                


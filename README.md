## Airbnb Clone
This is a fully-functional Airbnb clone built using Typescript, Next.js, MongoDB, Prisma, Tailwind, and NextAuth. It features a responsive and intuitive user interface that mimics the original Airbnb website, allowing users to search for, book, and manage their accommodations.

### View it live in [here](https://rent-property-jaoliveira98.vercel.app/ "Airbnb Clone").


## Features
- Authentication and authorization using NextAuth, allowing users to sign up, log in, and manage their profiles.
- Dynamic search functionality that retrieves data from a MongoDB database using Prisma.
- Booking system that allows users to select dates, view availability, and book.
- User-friendly interface with a responsive design using Tailwind CSS.
- Client panel that enables management of listings.

## Getting Started

1. Clone the repository by running the following command in your terminal:

```bash
git clone
```

2. Navigate to the project directory by running the following command:

```bash
cd airbnb
```

3. Install the project dependencies by running the following command:

```bash
npm install
```

4. Set up the .env file by creating a new file called .env in the root directory of the project and adding the following variables:

```javascript
DATABASE_URL=<your_database_connection_string>
GOOGLE_CLIENT_ID=<your_google_client_id>
GOOGLE_CLIENT_SECRET=<your_google_client_secret>
GITHUB_ID=<your_github_id>
GITHUB_SECRET=<your_github_secret>
NEXTAUTH_SECRET=<your_nextauth_secret>
```

Replace the placeholders with your own values.

5. Set up the Prisma ORM by running the following command:

```bash
npx prisma db push
```

6. Start the application by running the following command:

```bash
npm run dev
```

This will start the development server on **http://localhost:3000**.

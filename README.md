# Kudos remix-prisma-mongodb

Small fullstack demo App with Remix, Prisma, MongoDB & TailwindCSS, using AWS S3 bucket for image upload

## Starting demo app

In the project directory `kudos` , you can run :

```
npm install
```

and then to generate Prisma models run

```
npx prisma db push
```

and finally

```
npm run dev
```

Set `.env` file with environment variables :

```
DATABASE_URL="<mongodb database url>"
SESSION_SECRET="<your mongodb sessikon secret>"
KUDOS_ACCESS_KEY_ID="<access key ID>"
KUDOS_SECRET_ACCESS_KEY="<secret key>"
KUDOS_BUCKET_NAME="<s3 bucket name>"
KUDOS_BUCKET_REGION="<s3 bucket region>"
```

Running the demo app in the development mode.
Open http://localhost:3000 to view it in the browser.

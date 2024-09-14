## <a name="introduction">🤖 Introduction</a>

Built with Next.js, Horizon is a financial SaaS platform that connects to multiple bank accounts, displays transactions in real-time, allows users to transfer money to other platform users, and manages their finances altogether. 

## <a name="tech-stack">⚙️ Tech Stack</a>

- Next.js
- TypeScript
- Appwrite
- Plaid
- Dwolla
- React Hook Form
- Zod
- TailwindCSS
- Chart.js
- ShadCN

## <a name="features">🔋 Features</a>

👉 **Authentication**: An ultra-secure SSR authentication with proper validations and authorization

👉 **Connect Banks**: Integrates with Plaid for multiple bank account linking

👉 **Home Page**: Shows general overview of user account with total balance from all connected banks, recent transactions, money spent on different categories, etc

👉 **My Banks**: Check the complete list of all connected banks with respective balances, account details

👉 **Transaction History**: Includes pagination and filtering options for viewing transaction history of different banks

👉 **Real-time Updates**: Reflects changes across all relevant pages upon connecting new bank accounts.

👉 **Funds Transfer**: Allows users to transfer funds using Dwolla to other accounts with required fields and recipient bank ID.

👉 **Responsiveness**: Ensures the application adapts seamlessly to various screen sizes and devices, providing a consistent user experience across desktop, tablet, and mobile platforms.

and many more, including code architecture and reusability. 


**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
#NEXT
NEXT_PUBLIC_SITE_URL=

#APPWRITE
NEXT_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
NEXT_PUBLIC_APPWRITE_PROJECT=
APPWRITE_DATABASE_ID=
APPWRITE_USER_COLLECTION_ID=
APPWRITE_BANK_COLLECTION_ID=
APPWRITE_TRANSACTION_COLLECTION_ID=
APPWRITE_SECRET=

#PLAID
PLAID_CLIENT_ID=
PLAID_SECRET=
PLAID_ENV=
PLAID_PRODUCTS=
PLAID_COUNTRY_CODES=

#DWOLLA
DWOLLA_KEY=
DWOLLA_SECRET=
DWOLLA_BASE_URL=https://api-sandbox.dwolla.com
DWOLLA_ENV=sandbox

```

Replace the placeholder values with your actual respective account credentials. You can obtain these credentials by signing up on the [Appwrite](https://appwrite.io/?utm_source=youtube&utm_content=reactnative&ref=JSmastery), [Plaid](https://plaid.com/) and [Dwolla](https://www.dwolla.com/)




This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

![Screenshot 2024-09-13 114647](https://github.com/user-attachments/assets/eb556da7-b873-40e2-b845-709c23f8bd0f)

![Screenshot 2024-09-13 114732](https://github.com/user-attachments/assets/50de947b-8018-4bc5-ac89-138284ecb2e4)

![Screenshot 2024-09-13 104559](https://github.com/user-attachments/assets/3356a362-91ac-46de-9927-20ec9b918a35)

![Screenshot 2024-09-13 104807](https://github.com/user-attachments/assets/80ca5843-5503-4df5-b32f-a41990043883)

![Screenshot 2024-09-13 104852](https://github.com/user-attachments/assets/388aa1c0-eef4-4ed4-b530-e57646b899a8)

![Screenshot 2024-09-13 105023](https://github.com/user-attachments/assets/238e7450-ef34-401a-aa5d-89da3937237e)

![Screenshot 2024-09-13 105058](https://github.com/user-attachments/assets/e823346c-76d7-4c3e-a1e2-d4202843dd36)

![Screenshot 2024-09-13 105151](https://github.com/user-attachments/assets/5647465d-3cf3-4975-995e-ef3da1a5ebb4)

![Screenshot 2024-09-13 105336](https://github.com/user-attachments/assets/f4ac2b0f-866c-4b24-82fa-e2b821f85691)

![Screenshot 2024-09-13 105410](https://github.com/user-attachments/assets/42b81767-a326-443d-a05d-bf88e5b2aa7c)

![Screenshot 2024-09-13 105439](https://github.com/user-attachments/assets/c17757f1-fe07-487e-aab4-69c190c36616)

![Screenshot 2024-09-13 105533](https://github.com/user-attachments/assets/6061cab2-a0b5-4de7-a722-faaad8e23158)

![Screenshot 2024-09-13 105533](https://github.com/user-attachments/assets/fe77282a-6bd7-48b9-ac17-b4035d675067)



![Screenshot 2024-09-13 105636](https://github.com/user-attachments/assets/42758252-137e-4fd4-8ccc-60ecc0a1011c)

![Screenshot 2024-09-13 105747](https://github.com/user-attachments/assets/5cb019b3-7787-4c19-ae1b-353e910e3e38)

![Screenshot 2024-09-14 220959](https://github.com/user-attachments/assets/55b96b06-b2f9-4bd1-b036-0eb103c1a44b)

![Screenshot 2024-09-14 221100](https://github.com/user-attachments/assets/8e9eb225-7df4-4017-9ee2-8433bb592460)

![Screenshot 2024-09-14 235719](https://github.com/user-attachments/assets/7fd7ef18-fcb0-46b7-8142-2eb6c1664130)


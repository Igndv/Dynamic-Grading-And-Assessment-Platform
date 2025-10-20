## Dynamic Grading & Assessment Platform by Ignasius Deva

This project is a web-based application designed to provide educators with a flexible and powerful tool for creating dynamic student score sheets. Moving beyond the limitations of rigid spreadsheets, this platform empowers teachers to design their own grading structures from the ground up, tailored precisely to their curriculum and evaluation methodology.

The core feature of the system is its complete customizability. Teachers can define an unlimited number of grading "aspects" (e.g., "Homework," "Final Project," "Class Participation") and assign a specific weight to each. Within each aspect, they can further break down the assessment by adding unlimited "parameters" (e.g., "Essay," "Presentation," "Source Code Quality"), each with its own relative weight.

The platform automates the entire calculation process. As teachers input grades for each parameter, the system automatically computes the weighted score for each aspect and aggregates them into a final numerical grade for the student.

Based on this final score, the system instantly assigns two key indicators:

Letter Grade Predicate: Automatically assigns a grade of A, B, C, D, or E.

Academic Status: Automatically determines if the student has "Passed" or "Failed."

All thresholds for letter grades and the pass/fail status are fully customizable by the teacher, allowing the system to adapt to any school's or class's specific grading scale. This project aims to save teachers significant time on administrative work while providing a more accurate and transparent assessment of student performance.

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

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

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

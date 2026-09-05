# EstateX — Full Source (single file)

Every file from the project below, in fenced code blocks labeled with its path. Copy each block into a file at the matching path to reconstruct the project.

## `.gitignore`

```text
# dependencies
/node_modules

# next.js
/.next/
/out/

# production
/build

# misc
.DS_Store
*.pem

# debug
npm-debug.log*
yarn-debug.log*
yarn-error.log*

# local env files
.env*.local
.env

# typescript
*.tsbuildinfo
next-env.d.ts

```

## `README.md`

```md
# EstateX

A modern real-estate marketplace frontend for the Lagos property market, built with Next.js (App Router), TypeScript, and Tailwind CSS.

> This is **Frontend Phase 1** — a prototype using mock data. No backend, database, authentication, payments, or messaging are connected yet.

## Getting started

```bash
npm install
npm run dev
```

Then open [http://localhost:3000](http://localhost:3000).

To type-check and build for production:

```bash
npm run build
```

## Tech stack

- Next.js 14 (App Router)
- TypeScript
- Tailwind CSS
- Lucide React icons

## Project structure

```
app/
  about/            About page
  agents/           Agents directory
  contact/          Contact page + form
  dashboard/        User dashboard (mock stats + saved properties)
  login/            Sign in screen
  properties/
    [id]/           Dynamic property detail page
    page.tsx        Property marketplace with filters
  register/         Create account screen
  globals.css
  layout.tsx
  page.tsx          Homepage
components/         Reusable UI: Navbar, Footer, PropertyCard, PropertySearch, SectionHeading
data/properties.ts  Mock property data
types/property.ts   Property type definition
```

## Routes

| Route                | Description                       |
|-----------------------|------------------------------------|
| `/`                   | Homepage                          |
| `/properties`         | Property marketplace with filters |
| `/properties/[id]`    | Property detail page               |
| `/agents`             | Agents directory                  |
| `/about`              | About EstateX                     |
| `/contact`            | Contact form                      |
| `/login`              | Sign in (frontend only)           |
| `/register`           | Create account (frontend only)    |
| `/dashboard`          | User dashboard (mock data)        |

## Known limitations (Phase 1)

- No backend, database, or real API — all data is mocked in `data/properties.ts`.
- Login/register forms do not authenticate; there is no session handling.
- Search/filtering runs entirely client-side against the mock data.
- "Contact Agent," "Schedule Inspection," and messaging are UI-only.

## Planned architecture (future phase)

```
Next.js frontend → NestJS REST API → PostgreSQL
```

Planned entities: Users, Properties, Agents, Favorites, Messages, Inspections.

```

## `app/about/page.tsx`

```tsx
import { ShieldCheck, Users2, Gem } from "lucide-react";
import Navbar from "@/components/Navbar";
import Footer from "@/components/Footer";
import SectionHeading from "@/components/SectionHeading";

export const metadata = {
  title: "About | EstateX",
  description: "Learn how EstateX helps people find homes and connect with trusted agents in Lagos.",
};

const pillars = [
  {
    icon: ShieldCheck,
    title: "Trust",
    description:
      "Every property and agent on EstateX is verified before it appears in search results, so you can browse with confidence.",
  },
  {
    icon: Users2,
    title: "Community",
    description:
      "We connect buyers, tenants and agents across Lagos, building relationships that outlast a single transaction.",
  },
  {
    icon: Gem,
    title: "Quality Properties",
    description:
      "From starter apartments to executive penthouses, our listings are curated to match real budgets and real neighbourhoods.",
  },
];

export default function AboutPage() {
  return (
    <>
      <Navbar />

      <section className="bg-dark">
        <div className="container-x py-20 sm:py-28 text-center">
          <h1 className="text-3xl sm:text-5xl font-bold text-white max-w-2xl mx-auto leading-tight">
            Real estate made simpler.
          </h1>
          <p className="mt-5 text-slate-300 max-w-xl mx-auto text-base sm:text-lg">
            EstateX helps people discover properties and connect with trusted
            agents, without the usual back-and-forth of finding a home in
            Lagos.
          </p>
        </div>
      </section>

      <section className="container-x py-16 sm:py-20">
        <SectionHeading
          eyebrow="Our approach"
          heading="What EstateX stands for"
          description="Three principles guide every listing we publish and every agent we work with."
        />

        <div className="mt-10 grid grid-cols-1 sm:grid-cols-3 gap-6">
          {pillars.map(({ icon: Icon, title, description }) => (
            <div
              key={title}
              className="rounded-2xl border border-slate-200 p-7 hover:shadow-card transition-shadow"
            >
              <span className="flex h-12 w-12 items-center justify-center rounded-xl bg-orange-50 text-orange">
                <Icon size={22} />
              </span>
              <h3 className="mt-5 font-semibold text-dark text-lg">{title}</h3>
              <p className="mt-2 text-sm text-slate-600 leading-relaxed">
                {description}
              </p>
            </div>
          ))}
        </div>
      </section>

      <section className="container-x pb-16 sm:pb-20">
        <div className="rounded-2xl bg-slate-50 border border-slate-100 px-6 py-12 sm:px-14 sm:py-14">
          <div className="max-w-2xl">
            <h2 className="text-2xl sm:text-3xl font-bold text-dark">
              Built for the Lagos property market
            </h2>
            <p className="mt-4 text-slate-600 leading-relaxed">
              From Lekki and Ikoyi to Yaba and Ajah, we work directly with
              agents who understand each neighbourhood — its pricing,
              paperwork, and pace. Our goal is a marketplace where finding a
              home feels straightforward, not stressful.
            </p>
          </div>
        </div>
      </section>

      <Footer />
    </>
  );
}

```

## `app/agents/page.tsx`

```tsx
import Image from "next/image";
import { BadgeCheck, MapPin, Phone } from "lucide-react";
import Navbar from "@/components/Navbar";
import Footer from "@/components/Footer";
import SectionHeading from "@/components/SectionHeading";

export const metadata = {
  title: "Agents | EstateX",
  description: "Meet the verified real-estate agents on EstateX.",
};

const agents = [
  {
    name: "Chidinma Eze",
    location: "Lekki, Lagos",
    description:
      "Specialises in luxury duplexes and gated estates across the Lekki-Epe corridor, with 8 years in Lagos real estate.",
    image: "https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?w=400&q=80",
  },
  {
    name: "Tunde Bakare",
    location: "Ikoyi, Lagos",
    description:
      "Focused on high-end family homes and waterfront properties in Ikoyi and Banana Island.",
    image: "https://images.unsplash.com/photo-1560250097-0b93528c311a?w=400&q=80",
  },
  {
    name: "Amaka Nwosu",
    location: "Victoria Island, Lagos",
    description:
      "Helps corporate tenants and expatriates find serviced apartments on Victoria Island.",
    image: "https://images.unsplash.com/photo-1580489944761-15a19d654956?w=400&q=80",
  },
  {
    name: "Ibrahim Suleiman",
    location: "Ajah, Lagos",
    description:
      "Works with first-time buyers on affordable homes and villas in the fast-growing Ajah axis.",
    image: "https://images.unsplash.com/photo-1633332755192-727a05c4013d?w=400&q=80",
  },
  {
    name: "Ngozi Adeyemi",
    location: "Yaba, Lagos",
    description:
      "Rental specialist for young professionals and students around the Yaba tech corridor.",
    image: "https://images.unsplash.com/photo-1580489944761-15a19d654956?w=400&q=80",
  },
  {
    name: "Emeka Chukwu",
    location: "Banana Island, Lagos",
    description:
      "Represents premium penthouse and waterfront listings for high-net-worth buyers.",
    image: "https://images.unsplash.com/photo-1519085360753-af0119f7cbe7?w=400&q=80",
  },
];

export default function AgentsPage() {
  return (
    <>
      <Navbar />
      <section className="container-x py-12 sm:py-16">
        <SectionHeading
          eyebrow="Our network"
          heading="Meet our agents"
          description="Every agent on EstateX is vetted and verified before they can list a property."
        />

        <div className="mt-10 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
          {agents.map((agent) => (
            <div
              key={agent.name}
              className="rounded-2xl border border-slate-200 bg-white p-6 shadow-card hover:shadow-cardHover transition-shadow"
            >
              <div className="flex items-center gap-4">
                <div className="relative h-14 w-14 rounded-full overflow-hidden shrink-0">
                  <Image
                    src={agent.image}
                    alt={agent.name}
                    fill
                    sizes="56px"
                    className="object-cover"
                  />
                </div>
                <div>
                  <div className="flex items-center gap-1.5">
                    <h3 className="font-semibold text-dark">{agent.name}</h3>
                    <BadgeCheck size={16} className="text-orange" />
                  </div>
                  <p className="flex items-center gap-1 text-xs text-slate-500 mt-0.5">
                    <MapPin size={12} />
                    {agent.location}
                  </p>
                </div>
              </div>

              <p className="mt-4 text-sm text-slate-600 leading-relaxed">
                {agent.description}
              </p>

              <button
                type="button"
                className="mt-5 flex items-center justify-center gap-2 w-full rounded-lg border border-slate-200 py-2.5 text-sm font-semibold text-dark hover:bg-orange hover:text-white hover:border-orange transition-colors"
              >
                <Phone size={15} />
                Contact Agent
              </button>
            </div>
          ))}
        </div>
      </section>
      <Footer />
    </>
  );
}

```

## `app/contact/page.tsx`

```tsx
"use client";

import { FormEvent } from "react";
import { Mail, Phone, MapPin, Send } from "lucide-react";
import Navbar from "@/components/Navbar";
import Footer from "@/components/Footer";
import SectionHeading from "@/components/SectionHeading";

export default function ContactPage() {
  function handleSubmit(e: FormEvent) {
    e.preventDefault();
  }

  return (
    <>
      <Navbar />
      <section className="container-x py-12 sm:py-16">
        <SectionHeading
          eyebrow="Get in touch"
          heading="We'd love to hear from you"
          description="Questions about a listing, an agent, or EstateX itself? Send us a message."
        />

        <div className="mt-10 grid grid-cols-1 lg:grid-cols-3 gap-10">
          <div className="lg:col-span-1 space-y-5">
            <div className="flex items-start gap-3 rounded-2xl border border-slate-200 p-5">
              <span className="flex h-10 w-10 items-center justify-center rounded-lg bg-orange-50 text-orange shrink-0">
                <Mail size={18} />
              </span>
              <div>
                <p className="text-sm font-semibold text-dark">Email</p>
                <p className="text-sm text-slate-500">hello@estatex.ng</p>
              </div>
            </div>
            <div className="flex items-start gap-3 rounded-2xl border border-slate-200 p-5">
              <span className="flex h-10 w-10 items-center justify-center rounded-lg bg-orange-50 text-orange shrink-0">
                <Phone size={18} />
              </span>
              <div>
                <p className="text-sm font-semibold text-dark">Phone</p>
                <p className="text-sm text-slate-500">+234 801 234 5678</p>
              </div>
            </div>
            <div className="flex items-start gap-3 rounded-2xl border border-slate-200 p-5">
              <span className="flex h-10 w-10 items-center justify-center rounded-lg bg-orange-50 text-orange shrink-0">
                <MapPin size={18} />
              </span>
              <div>
                <p className="text-sm font-semibold text-dark">Office</p>
                <p className="text-sm text-slate-500">Lagos, Nigeria</p>
              </div>
            </div>
          </div>

          <form
            onSubmit={handleSubmit}
            className="lg:col-span-2 rounded-2xl border border-slate-200 p-6 sm:p-8 space-y-4"
          >
            <div className="grid grid-cols-1 sm:grid-cols-2 gap-4">
              <div>
                <label htmlFor="name" className="text-sm font-medium text-dark">
                  Name
                </label>
                <input
                  id="name"
                  type="text"
                  required
                  placeholder="Your full name"
                  className="mt-1.5 w-full rounded-xl border border-slate-200 px-3.5 py-3 text-sm outline-none focus:border-orange transition-colors placeholder:text-slate-400"
                />
              </div>
              <div>
                <label htmlFor="email" className="text-sm font-medium text-dark">
                  Email
                </label>
                <input
                  id="email"
                  type="email"
                  required
                  placeholder="you@example.com"
                  className="mt-1.5 w-full rounded-xl border border-slate-200 px-3.5 py-3 text-sm outline-none focus:border-orange transition-colors placeholder:text-slate-400"
                />
              </div>
            </div>

            <div>
              <label htmlFor="subject" className="text-sm font-medium text-dark">
                Subject
              </label>
              <input
                id="subject"
                type="text"
                required
                placeholder="How can we help?"
                className="mt-1.5 w-full rounded-xl border border-slate-200 px-3.5 py-3 text-sm outline-none focus:border-orange transition-colors placeholder:text-slate-400"
              />
            </div>

            <div>
              <label htmlFor="message" className="text-sm font-medium text-dark">
                Message
              </label>
              <textarea
                id="message"
                required
                rows={5}
                placeholder="Tell us a bit more..."
                className="mt-1.5 w-full rounded-xl border border-slate-200 px-3.5 py-3 text-sm outline-none focus:border-orange transition-colors placeholder:text-slate-400 resize-none"
              />
            </div>

            <button
              type="submit"
              className="flex items-center justify-center gap-2 rounded-xl bg-orange hover:bg-orange-600 transition-colors text-white text-sm font-semibold px-6 py-3.5 w-full sm:w-auto"
            >
              <Send size={16} />
              Send Message
            </button>
          </form>
        </div>
      </section>
      <Footer />
    </>
  );
}

```

## `app/dashboard/page.tsx`

```tsx
"use client";

import { useState } from "react";
import {
  LayoutGrid,
  Heart,
  MessageSquare,
  CalendarCheck,
  User,
  Menu,
  X,
} from "lucide-react";
import Navbar from "@/components/Navbar";
import Footer from "@/components/Footer";
import PropertyCard from "@/components/PropertyCard";
import { properties } from "@/data/properties";

const navItems = [
  { label: "Overview", icon: LayoutGrid },
  { label: "Saved Properties", icon: Heart },
  { label: "Messages", icon: MessageSquare },
  { label: "Inspections", icon: CalendarCheck },
  { label: "Profile", icon: User },
];

export default function DashboardPage() {
  const [active, setActive] = useState("Overview");
  const [mobileNavOpen, setMobileNavOpen] = useState(false);
  const saved = properties.slice(0, 3);

  return (
    <>
      <Navbar />
      <section className="container-x py-8 sm:py-12">
        <div className="flex items-center justify-between lg:hidden mb-4">
          <h1 className="text-xl font-bold text-dark">Dashboard</h1>
          <button
            type="button"
            onClick={() => setMobileNavOpen((v) => !v)}
            className="flex h-10 w-10 items-center justify-center rounded-lg border border-slate-200 text-dark"
            aria-label="Toggle dashboard navigation"
          >
            {mobileNavOpen ? <X size={20} /> : <Menu size={20} />}
          </button>
        </div>

        <div className="grid grid-cols-1 lg:grid-cols-[240px_1fr] gap-8">
          <aside
            className={`${
              mobileNavOpen ? "block" : "hidden"
            } lg:block rounded-2xl border border-slate-200 p-3 h-fit`}
          >
            <nav className="flex flex-col gap-1">
              {navItems.map(({ label, icon: Icon }) => (
                <button
                  key={label}
                  type="button"
                  onClick={() => {
                    setActive(label);
                    setMobileNavOpen(false);
                  }}
                  className={`flex items-center gap-3 rounded-lg px-3.5 py-2.5 text-sm font-medium transition-colors ${
                    active === label
                      ? "bg-orange text-white"
                      : "text-slate-600 hover:bg-slate-50"
                  }`}
                >
                  <Icon size={17} />
                  {label}
                </button>
              ))}
            </nav>
          </aside>

          <div>
            <h1 className="hidden lg:block text-2xl font-bold text-dark mb-6">
              Overview
            </h1>

            <div className="grid grid-cols-1 sm:grid-cols-3 gap-4">
              <div className="rounded-2xl border border-slate-200 p-6">
                <p className="text-sm text-slate-500">Saved Properties</p>
                <p className="mt-2 text-3xl font-bold text-dark">12</p>
              </div>
              <div className="rounded-2xl border border-slate-200 p-6">
                <p className="text-sm text-slate-500">Messages</p>
                <p className="mt-2 text-3xl font-bold text-dark">5</p>
              </div>
              <div className="rounded-2xl border border-slate-200 p-6">
                <p className="text-sm text-slate-500">Inspections</p>
                <p className="mt-2 text-3xl font-bold text-dark">3</p>
              </div>
            </div>

            <div className="mt-10">
              <h2 className="text-lg font-semibold text-dark mb-5">
                Saved Properties
              </h2>
              <div className="grid grid-cols-1 sm:grid-cols-2 xl:grid-cols-3 gap-6">
                {saved.map((property) => (
                  <PropertyCard key={property.id} property={property} />
                ))}
              </div>
            </div>
          </div>
        </div>
      </section>
      <Footer />
    </>
  );
}

```

## `app/globals.css`

```css
@tailwind base;
@tailwind components;
@tailwind utilities;

:root {
  --orange: #f97316;
  --dark: #0f172a;
}

html {
  scroll-behavior: smooth;
}

body {
  background-color: #ffffff;
  color: var(--dark);
  -webkit-font-smoothing: antialiased;
  text-rendering: optimizeLegibility;
}

::selection {
  background-color: #fed7aa;
  color: var(--dark);
}

a,
button {
  -webkit-tap-highlight-color: transparent;
}

button {
  cursor: pointer;
}

input,
select,
textarea {
  font: inherit;
}

/* Focus states for accessibility */
a:focus-visible,
button:focus-visible,
input:focus-visible,
select:focus-visible,
textarea:focus-visible {
  outline: 2px solid var(--orange);
  outline-offset: 2px;
}

@media (prefers-reduced-motion: reduce) {
  *,
  *::before,
  *::after {
    animation-duration: 0.001ms !important;
    animation-iteration-count: 1 !important;
    transition-duration: 0.001ms !important;
    scroll-behavior: auto !important;
  }
}

.container-x {
  max-width: 1280px;
  margin-left: auto;
  margin-right: auto;
  padding-left: 1.25rem;
  padding-right: 1.25rem;
}

@media (min-width: 1024px) {
  .container-x {
    padding-left: 2rem;
    padding-right: 2rem;
  }
}

```

## `app/layout.tsx`

```tsx
import type { Metadata } from "next";
import { Manrope } from "next/font/google";
import "./globals.css";

const manrope = Manrope({
  subsets: ["latin"],
  variable: "--font-sans",
  display: "swap",
});

export const metadata: Metadata = {
  title: "EstateX | Find a place you'll love",
  description: "Discover homes, apartments, land and commercial properties.",
};

export default function RootLayout({
  children,
}: Readonly<{
  children: React.ReactNode;
}>) {
  return (
    <html lang="en" className={manrope.variable}>
      <body className="font-sans">{children}</body>
    </html>
  );
}

```

## `app/login/page.tsx`

```tsx
"use client";

import Link from "next/link";
import { FormEvent } from "react";
import { Home, Mail, Lock } from "lucide-react";
import Navbar from "@/components/Navbar";
import Footer from "@/components/Footer";

export default function LoginPage() {
  function handleSubmit(e: FormEvent) {
    e.preventDefault();
  }

  return (
    <>
      <Navbar />
      <section className="container-x py-14 sm:py-20 flex justify-center">
        <div className="w-full max-w-md">
          <div className="flex flex-col items-center text-center">
            <span className="flex h-11 w-11 items-center justify-center rounded-xl bg-orange text-white mb-4">
              <Home size={20} strokeWidth={2.5} />
            </span>
            <h1 className="text-2xl font-bold text-dark">Welcome back</h1>
            <p className="mt-2 text-sm text-slate-500">
              Sign in to manage your saved properties and messages.
            </p>
          </div>

          <form onSubmit={handleSubmit} className="mt-8 space-y-4">
            <div>
              <label htmlFor="email" className="text-sm font-medium text-dark">
                Email
              </label>
              <div className="mt-1.5 flex items-center gap-2 rounded-xl border border-slate-200 px-3.5 py-3 focus-within:border-orange transition-colors">
                <Mail size={17} className="text-slate-400" />
                <input
                  id="email"
                  type="email"
                  required
                  placeholder="you@example.com"
                  className="w-full text-sm outline-none placeholder:text-slate-400 bg-transparent"
                />
              </div>
            </div>

            <div>
              <label htmlFor="password" className="text-sm font-medium text-dark">
                Password
              </label>
              <div className="mt-1.5 flex items-center gap-2 rounded-xl border border-slate-200 px-3.5 py-3 focus-within:border-orange transition-colors">
                <Lock size={17} className="text-slate-400" />
                <input
                  id="password"
                  type="password"
                  required
                  placeholder="••••••••"
                  className="w-full text-sm outline-none placeholder:text-slate-400 bg-transparent"
                />
              </div>
              <div className="mt-2 text-right">
                <Link href="#" className="text-xs font-medium text-orange">
                  Forgot password?
                </Link>
              </div>
            </div>

            <button
              type="submit"
              className="w-full rounded-xl bg-orange hover:bg-orange-600 transition-colors text-white text-sm font-semibold py-3.5"
            >
              Sign In
            </button>
          </form>

          <p className="mt-6 text-center text-sm text-slate-500">
            Don&apos;t have an account?{" "}
            <Link href="/register" className="font-semibold text-orange">
              Create an account
            </Link>
          </p>

          <p className="mt-8 text-center text-xs text-slate-400">
            This is a frontend prototype. Authentication is not yet connected.
          </p>
        </div>
      </section>
      <Footer />
    </>
  );
}

```

## `app/page.tsx`

```tsx
import Image from "next/image";
import Link from "next/link";
import { ShieldCheck, Building, Users, ArrowRight } from "lucide-react";
import Navbar from "@/components/Navbar";
import Footer from "@/components/Footer";
import PropertySearch from "@/components/PropertySearch";
import PropertyCard from "@/components/PropertyCard";
import SectionHeading from "@/components/SectionHeading";
import { properties } from "@/data/properties";

const categories = [
  {
    label: "Apartments",
    query: "Apartment",
    image:
      "https://images.unsplash.com/photo-1522708323590-d24dbb6b0267?w=800&q=80",
  },
  {
    label: "Houses",
    query: "House",
    image:
      "https://images.unsplash.com/photo-1568605114967-8130f3a36994?w=800&q=80",
  },
  {
    label: "Luxury Villas",
    query: "Villa",
    image:
      "https://images.unsplash.com/photo-1600047509807-ba8f99d2cdde?w=800&q=80",
  },
  {
    label: "Land",
    query: "Land",
    image:
      "https://images.unsplash.com/photo-1500382017468-9049fed747ef?w=800&q=80",
  },
];

export default function HomePage() {
  const featured = properties.filter((p) => p.featured);

  return (
    <>
      <Navbar />

      {/* Hero */}
      <section className="relative isolate">
        <div className="absolute inset-0 -z-10">
          <Image
            src="https://images.unsplash.com/photo-1600596542815-ffad4c1539a9?w=1920&q=80"
            alt="Modern home exterior in Lagos"
            fill
            priority
            className="object-cover"
          />
          <div className="absolute inset-0 bg-dark/70" />
          <div className="absolute inset-0 bg-gradient-to-t from-dark/80 via-dark/40 to-dark/60" />
        </div>

        <div className="container-x pt-20 pb-28 sm:pt-28 sm:pb-36">
          <div className="max-w-2xl">
            <h1 className="text-4xl sm:text-5xl lg:text-6xl font-bold tracking-tight text-white leading-[1.1]">
              Find a place you&apos;ll love.
            </h1>
            <p className="mt-5 text-base sm:text-lg text-slate-200 max-w-xl">
              Discover beautiful homes, apartments, land and commercial
              properties from trusted agents across Lagos.
            </p>
            <div className="mt-8 flex flex-wrap gap-3">
              <Link
                href="/properties"
                className="inline-flex items-center gap-2 rounded-lg bg-orange hover:bg-orange-600 transition-colors text-white text-sm font-semibold px-6 py-3.5"
              >
                Browse Properties
                <ArrowRight size={16} />
              </Link>
              <Link
                href="/register"
                className="inline-flex items-center gap-2 rounded-lg bg-white/10 border border-white/30 hover:bg-white/20 transition-colors text-white text-sm font-semibold px-6 py-3.5"
              >
                List a Property
              </Link>
            </div>
          </div>
        </div>

        <div className="container-x -mt-14 sm:-mt-16 relative pb-2">
          <PropertySearch />
        </div>
      </section>

      {/* Trust features */}
      <section className="border-b border-slate-100">
        <div className="container-x py-14 grid grid-cols-1 sm:grid-cols-3 gap-8">
          <div className="flex items-start gap-4">
            <span className="flex h-11 w-11 shrink-0 items-center justify-center rounded-xl bg-orange-50 text-orange">
              <ShieldCheck size={22} />
            </span>
            <div>
              <h3 className="font-semibold text-dark">Verified Properties</h3>
              <p className="mt-1 text-sm text-slate-600">
                Every listing is checked before it goes live.
              </p>
            </div>
          </div>
          <div className="flex items-start gap-4">
            <span className="flex h-11 w-11 shrink-0 items-center justify-center rounded-xl bg-orange-50 text-orange">
              <Building size={22} />
            </span>
            <div>
              <h3 className="font-semibold text-dark">Thousands of Listings</h3>
              <p className="mt-1 text-sm text-slate-600">
                From studio apartments to full estates across Lagos.
              </p>
            </div>
          </div>
          <div className="flex items-start gap-4">
            <span className="flex h-11 w-11 shrink-0 items-center justify-center rounded-xl bg-orange-50 text-orange">
              <Users size={22} />
            </span>
            <div>
              <h3 className="font-semibold text-dark">Professional Agents</h3>
              <p className="mt-1 text-sm text-slate-600">
                Work with agents who know the local market inside out.
              </p>
            </div>
          </div>
        </div>
      </section>

      {/* Featured properties */}
      <section className="py-16 sm:py-20">
        <div className="container-x">
          <div className="flex flex-col sm:flex-row sm:items-end sm:justify-between gap-4">
            <SectionHeading
              eyebrow="Handpicked"
              heading="Featured properties"
              description="A selection of our most sought-after listings this month."
            />
            <Link
              href="/properties"
              className="hidden sm:inline-flex items-center gap-1.5 text-sm font-semibold text-orange shrink-0"
            >
              View all properties
              <ArrowRight size={15} />
            </Link>
          </div>

          <div className="mt-10 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
            {featured.map((property) => (
              <PropertyCard key={property.id} property={property} />
            ))}
          </div>

          <Link
            href="/properties"
            className="sm:hidden mt-8 flex items-center justify-center gap-1.5 text-sm font-semibold text-orange"
          >
            View all properties
            <ArrowRight size={15} />
          </Link>
        </div>
      </section>

      {/* Browse by type */}
      <section className="py-16 sm:py-20 bg-slate-50 border-y border-slate-100">
        <div className="container-x">
          <SectionHeading
            eyebrow="Categories"
            heading="Browse by property type"
            description="Looking for something specific? Start with a category."
          />

          <div className="mt-10 grid grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-6">
            {categories.map((cat) => (
              <Link
                key={cat.label}
                href={`/properties?type=${encodeURIComponent(cat.query)}`}
                className="group relative h-40 sm:h-52 rounded-2xl overflow-hidden"
              >
                <Image
                  src={cat.image}
                  alt={cat.label}
                  fill
                  sizes="(max-width: 768px) 50vw, 25vw"
                  className="object-cover group-hover:scale-105 transition-transform duration-500"
                />
                <div className="absolute inset-0 bg-gradient-to-t from-dark/80 via-dark/10 to-transparent" />
                <span className="absolute bottom-4 left-4 text-white font-semibold text-sm sm:text-base">
                  {cat.label}
                </span>
              </Link>
            ))}
          </div>
        </div>
      </section>

      {/* List your property CTA */}
      <section className="py-16 sm:py-20">
        <div className="container-x">
          <div className="rounded-2xl bg-orange px-6 py-12 sm:px-14 sm:py-16 text-center sm:text-left sm:flex sm:items-center sm:justify-between gap-8">
            <div>
              <h2 className="text-2xl sm:text-3xl font-bold text-white max-w-lg">
                Have a property to list?
              </h2>
              <p className="mt-3 text-sm sm:text-base text-orange-50 max-w-md">
                Reach thousands of verified buyers and tenants searching for
                their next home across Lagos.
              </p>
            </div>
            <Link
              href="/register"
              className="mt-6 sm:mt-0 inline-flex items-center gap-2 rounded-lg bg-white hover:bg-orange-50 transition-colors text-orange text-sm font-semibold px-6 py-3.5 shrink-0"
            >
              List a Property
              <ArrowRight size={16} />
            </Link>
          </div>
        </div>
      </section>

      <Footer />
    </>
  );
}

```

## `app/properties/PropertiesBrowser.tsx`

```tsx
"use client";

import { useMemo, useState } from "react";
import { useSearchParams } from "next/navigation";
import { SearchX, SlidersHorizontal } from "lucide-react";
import PropertyCard from "@/components/PropertyCard";
import SectionHeading from "@/components/SectionHeading";
import { properties } from "@/data/properties";

const propertyTypes = ["Any Type", "Apartment", "House", "Villa", "Land", "Commercial"];
const listingTypes = ["Any Purpose", "For Sale", "For Rent", "Shortlet"];

export default function PropertiesBrowser() {
  const searchParams = useSearchParams();

  const [query, setQuery] = useState(searchParams.get("location") ?? "");
  const [type, setType] = useState(searchParams.get("type") ?? "Any Type");
  const [listingType, setListingType] = useState(() => {
    const purpose = searchParams.get("purpose");
    if (purpose === "Buy") return "For Sale";
    if (purpose === "Rent") return "For Rent";
    if (purpose === "Shortlet") return "Shortlet";
    return "Any Purpose";
  });

  const filtered = useMemo(() => {
    const q = query.trim().toLowerCase();
    return properties.filter((property) => {
      const matchesQuery =
        !q ||
        property.title.toLowerCase().includes(q) ||
        property.location.toLowerCase().includes(q) ||
        property.city.toLowerCase().includes(q);
      const matchesType = type === "Any Type" || property.type === type;
      const matchesListingType =
        listingType === "Any Purpose" || property.listingType === listingType;
      return matchesQuery && matchesType && matchesListingType;
    });
  }, [query, type, listingType]);

  return (
    <section className="container-x py-12 sm:py-16">
      <SectionHeading
        eyebrow="Marketplace"
        heading="Find your next property"
        description="Search and filter verified listings from agents across Lagos."
      />

      <div className="mt-8 rounded-2xl border border-slate-200 bg-white p-4 sm:p-5">
        <div className="flex flex-col lg:flex-row gap-3">
          <input
            type="text"
            value={query}
            onChange={(e) => setQuery(e.target.value)}
            placeholder="Search by title or location"
            className="flex-1 rounded-xl border border-slate-200 px-4 py-3 text-sm outline-none focus:border-orange transition-colors"
          />
          <select
            value={type}
            onChange={(e) => setType(e.target.value)}
            className="rounded-xl border border-slate-200 px-4 py-3 text-sm outline-none focus:border-orange transition-colors bg-white text-dark lg:w-52"
          >
            {propertyTypes.map((t) => (
              <option key={t} value={t}>
                {t}
              </option>
            ))}
          </select>
          <select
            value={listingType}
            onChange={(e) => setListingType(e.target.value)}
            className="rounded-xl border border-slate-200 px-4 py-3 text-sm outline-none focus:border-orange transition-colors bg-white text-dark lg:w-52"
          >
            {listingTypes.map((t) => (
              <option key={t} value={t}>
                {t}
              </option>
            ))}
          </select>
          <button
            type="button"
            className="flex items-center justify-center gap-2 rounded-xl bg-orange hover:bg-orange-600 transition-colors text-white text-sm font-semibold px-6 py-3 shrink-0"
          >
            <SlidersHorizontal size={16} />
            Filter
          </button>
        </div>
      </div>

      <p className="mt-6 text-sm text-slate-500">
        {filtered.length} {filtered.length === 1 ? "property" : "properties"} found
      </p>

      {filtered.length > 0 ? (
        <div className="mt-6 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
          {filtered.map((property) => (
            <PropertyCard key={property.id} property={property} />
          ))}
        </div>
      ) : (
        <div className="mt-6 flex flex-col items-center justify-center rounded-2xl border border-dashed border-slate-300 py-20 text-center">
          <span className="flex h-14 w-14 items-center justify-center rounded-full bg-orange-50 text-orange mb-4">
            <SearchX size={26} />
          </span>
          <h3 className="text-lg font-semibold text-dark">No properties match your search</h3>
          <p className="mt-1.5 text-sm text-slate-500 max-w-sm">
            Try a different location or clear a filter to see more listings.
          </p>
          <button
            type="button"
            onClick={() => {
              setQuery("");
              setType("Any Type");
              setListingType("Any Purpose");
            }}
            className="mt-5 text-sm font-semibold text-orange"
          >
            Clear all filters
          </button>
        </div>
      )}
    </section>
  );
}

```

## `app/properties/[id]/page.tsx`

```tsx
import Image from "next/image";
import Link from "next/link";
import {
  Bed,
  Bath,
  Ruler,
  MapPin,
  Home,
  ArrowLeft,
  Phone,
  CalendarCheck,
  SearchX,
} from "lucide-react";
import Navbar from "@/components/Navbar";
import Footer from "@/components/Footer";
import { properties } from "@/data/properties";

export function generateStaticParams() {
  return properties.map((property) => ({ id: String(property.id) }));
}

export default function PropertyDetailPage({
  params,
}: {
  params: { id: string };
}) {
  const property = properties.find((p) => p.id === Number(params.id));

  if (!property) {
    return (
      <>
        <Navbar />
        <section className="container-x py-24 flex flex-col items-center text-center">
          <span className="flex h-14 w-14 items-center justify-center rounded-full bg-orange-50 text-orange mb-4">
            <SearchX size={26} />
          </span>
          <h1 className="text-2xl font-bold text-dark">Property not found</h1>
          <p className="mt-2 text-sm text-slate-500 max-w-sm">
            This listing may have been removed or the link is incorrect.
          </p>
          <Link
            href="/properties"
            className="mt-6 inline-flex items-center gap-2 rounded-lg bg-orange text-white text-sm font-semibold px-5 py-3"
          >
            <ArrowLeft size={16} />
            Back to Properties
          </Link>
        </section>
        <Footer />
      </>
    );
  }

  return (
    <>
      <Navbar />
      <section className="container-x py-8 sm:py-12">
        <Link
          href="/properties"
          className="inline-flex items-center gap-1.5 text-sm font-medium text-slate-500 hover:text-dark transition-colors"
        >
          <ArrowLeft size={15} />
          Back to Properties
        </Link>

        <div className="mt-6 grid grid-cols-1 lg:grid-cols-3 gap-10">
          <div className="lg:col-span-2">
            <div className="relative h-64 sm:h-96 rounded-2xl overflow-hidden">
              <Image
                src={property.image}
                alt={property.title}
                fill
                sizes="(max-width: 1024px) 100vw, 66vw"
                className="object-cover"
                priority
              />
              <span className="absolute top-4 left-4 rounded-md bg-white px-3 py-1.5 text-xs font-semibold text-dark shadow-sm">
                {property.listingType}
              </span>
            </div>

            <div className="mt-6">
              <h1 className="text-2xl sm:text-3xl font-bold text-dark">
                {property.title}
              </h1>
              <p className="mt-2 flex items-center gap-1.5 text-sm text-slate-500">
                <MapPin size={15} />
                {property.location}, {property.city}
              </p>

              <div className="mt-6 flex flex-wrap gap-6 border-y border-slate-100 py-5">
                <span className="flex items-center gap-2 text-sm text-slate-700">
                  <Bed size={18} className="text-orange" />
                  {property.bedrooms} Bedrooms
                </span>
                <span className="flex items-center gap-2 text-sm text-slate-700">
                  <Bath size={18} className="text-orange" />
                  {property.bathrooms} Bathrooms
                </span>
                <span className="flex items-center gap-2 text-sm text-slate-700">
                  <Ruler size={18} className="text-orange" />
                  {property.area}
                </span>
                <span className="flex items-center gap-2 text-sm text-slate-700">
                  <Home size={18} className="text-orange" />
                  {property.type}
                </span>
              </div>

              <div className="mt-6">
                <h2 className="text-lg font-semibold text-dark">Description</h2>
                <p className="mt-3 text-sm sm:text-base text-slate-600 leading-relaxed">
                  {property.description}
                </p>
              </div>
            </div>
          </div>

          <aside className="lg:col-span-1">
            <div className="rounded-2xl border border-slate-200 bg-white p-6 sticky top-24">
              <p className="text-sm text-slate-500">Price</p>
              <p className="mt-1 text-3xl font-bold text-orange">
                {property.priceLabel}
              </p>

              <div className="mt-6 flex flex-col gap-3">
                <button
                  type="button"
                  className="flex items-center justify-center gap-2 rounded-lg bg-orange hover:bg-orange-600 transition-colors text-white text-sm font-semibold py-3.5"
                >
                  <Phone size={16} />
                  Contact Agent
                </button>
                <button
                  type="button"
                  className="flex items-center justify-center gap-2 rounded-lg border border-slate-200 hover:bg-slate-50 transition-colors text-dark text-sm font-semibold py-3.5"
                >
                  <CalendarCheck size={16} />
                  Schedule Inspection
                </button>
              </div>

              <p className="mt-5 text-xs text-slate-400 leading-relaxed">
                Agent messaging and inspection scheduling are coming soon.
                This is currently a frontend prototype.
              </p>
            </div>
          </aside>
        </div>
      </section>
      <Footer />
    </>
  );
}

```

## `app/properties/page.tsx`

```tsx
import { Suspense } from "react";
import Navbar from "@/components/Navbar";
import Footer from "@/components/Footer";
import PropertiesBrowser from "./PropertiesBrowser";

export const metadata = {
  title: "Properties | EstateX",
  description: "Browse verified properties for sale and rent across Lagos.",
};

export default function PropertiesPage() {
  return (
    <>
      <Navbar />
      <Suspense fallback={null}>
        <PropertiesBrowser />
      </Suspense>
      <Footer />
    </>
  );
}

```

## `app/register/page.tsx`

```tsx
"use client";

import Link from "next/link";
import { FormEvent } from "react";
import { Home, User, Mail, Lock } from "lucide-react";
import Navbar from "@/components/Navbar";
import Footer from "@/components/Footer";

export default function RegisterPage() {
  function handleSubmit(e: FormEvent) {
    e.preventDefault();
  }

  return (
    <>
      <Navbar />
      <section className="container-x py-14 sm:py-20 flex justify-center">
        <div className="w-full max-w-md">
          <div className="flex flex-col items-center text-center">
            <span className="flex h-11 w-11 items-center justify-center rounded-xl bg-orange text-white mb-4">
              <Home size={20} strokeWidth={2.5} />
            </span>
            <h1 className="text-2xl font-bold text-dark">Create your account</h1>
            <p className="mt-2 text-sm text-slate-500">
              Join EstateX to save properties and list with agents.
            </p>
          </div>

          <form onSubmit={handleSubmit} className="mt-8 space-y-4">
            <div>
              <label htmlFor="name" className="text-sm font-medium text-dark">
                Full name
              </label>
              <div className="mt-1.5 flex items-center gap-2 rounded-xl border border-slate-200 px-3.5 py-3 focus-within:border-orange transition-colors">
                <User size={17} className="text-slate-400" />
                <input
                  id="name"
                  type="text"
                  required
                  placeholder="Ada Okafor"
                  className="w-full text-sm outline-none placeholder:text-slate-400 bg-transparent"
                />
              </div>
            </div>

            <div>
              <label htmlFor="email" className="text-sm font-medium text-dark">
                Email
              </label>
              <div className="mt-1.5 flex items-center gap-2 rounded-xl border border-slate-200 px-3.5 py-3 focus-within:border-orange transition-colors">
                <Mail size={17} className="text-slate-400" />
                <input
                  id="email"
                  type="email"
                  required
                  placeholder="you@example.com"
                  className="w-full text-sm outline-none placeholder:text-slate-400 bg-transparent"
                />
              </div>
            </div>

            <div>
              <label htmlFor="password" className="text-sm font-medium text-dark">
                Password
              </label>
              <div className="mt-1.5 flex items-center gap-2 rounded-xl border border-slate-200 px-3.5 py-3 focus-within:border-orange transition-colors">
                <Lock size={17} className="text-slate-400" />
                <input
                  id="password"
                  type="password"
                  required
                  placeholder="••••••••"
                  className="w-full text-sm outline-none placeholder:text-slate-400 bg-transparent"
                />
              </div>
            </div>

            <div>
              <label htmlFor="confirm" className="text-sm font-medium text-dark">
                Confirm password
              </label>
              <div className="mt-1.5 flex items-center gap-2 rounded-xl border border-slate-200 px-3.5 py-3 focus-within:border-orange transition-colors">
                <Lock size={17} className="text-slate-400" />
                <input
                  id="confirm"
                  type="password"
                  required
                  placeholder="••••••••"
                  className="w-full text-sm outline-none placeholder:text-slate-400 bg-transparent"
                />
              </div>
            </div>

            <button
              type="submit"
              className="w-full rounded-xl bg-orange hover:bg-orange-600 transition-colors text-white text-sm font-semibold py-3.5"
            >
              Create Account
            </button>
          </form>

          <p className="mt-6 text-center text-sm text-slate-500">
            Already have an account?{" "}
            <Link href="/login" className="font-semibold text-orange">
              Sign in
            </Link>
          </p>

          <p className="mt-8 text-center text-xs text-slate-400">
            This is a frontend prototype. Authentication is not yet connected.
          </p>
        </div>
      </section>
      <Footer />
    </>
  );
}

```

## `components/Footer.tsx`

```tsx
import Link from "next/link";
import { Home, MapPin, Mail, Phone } from "lucide-react";

export default function Footer() {
  return (
    <footer className="bg-dark text-slate-300">
      <div className="container-x py-14 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-10">
        <div>
          <Link href="/" className="flex items-center gap-2">
            <span className="flex h-9 w-9 items-center justify-center rounded-lg bg-orange text-white">
              <Home size={18} strokeWidth={2.5} />
            </span>
            <span className="text-lg font-bold text-white">
              Estate<span className="text-orange">X</span>
            </span>
          </Link>
          <p className="mt-4 text-sm text-slate-400 max-w-xs">
            Find a place you&apos;ll love.
          </p>
        </div>

        <div>
          <h4 className="text-sm font-semibold text-white mb-4">Explore</h4>
          <ul className="space-y-3 text-sm">
            <li>
              <Link href="/properties" className="hover:text-orange transition-colors">
                Properties
              </Link>
            </li>
            <li>
              <Link href="/agents" className="hover:text-orange transition-colors">
                Agents
              </Link>
            </li>
            <li>
              <Link href="/about" className="hover:text-orange transition-colors">
                About
              </Link>
            </li>
            <li>
              <Link href="/contact" className="hover:text-orange transition-colors">
                Contact
              </Link>
            </li>
          </ul>
        </div>

        <div>
          <h4 className="text-sm font-semibold text-white mb-4">For Agents</h4>
          <ul className="space-y-3 text-sm">
            <li>
              <Link href="/register" className="hover:text-orange transition-colors">
                List a Property
              </Link>
            </li>
            <li>
              <Link href="/dashboard" className="hover:text-orange transition-colors">
                Agent Dashboard
              </Link>
            </li>
          </ul>
        </div>

        <div>
          <h4 className="text-sm font-semibold text-white mb-4">Contact</h4>
          <ul className="space-y-3 text-sm">
            <li className="flex items-start gap-2">
              <MapPin size={16} className="mt-0.5 text-orange shrink-0" />
              <span>Lagos, Nigeria</span>
            </li>
            <li className="flex items-start gap-2">
              <Mail size={16} className="mt-0.5 text-orange shrink-0" />
              <span>hello@estatex.ng</span>
            </li>
            <li className="flex items-start gap-2">
              <Phone size={16} className="mt-0.5 text-orange shrink-0" />
              <span>+234 801 234 5678</span>
            </li>
          </ul>
        </div>
      </div>

      <div className="border-t border-white/10">
        <div className="container-x py-6 text-xs text-slate-500 flex flex-col sm:flex-row gap-2 sm:justify-between">
          <span>© {new Date().getFullYear()} EstateX. All rights reserved.</span>
          <span>Built for the Lagos property market.</span>
        </div>
      </div>
    </footer>
  );
}

```

## `components/Navbar.tsx`

```tsx
"use client";

import Link from "next/link";
import { useState } from "react";
import { Menu, X, Home } from "lucide-react";

const navLinks = [
  { label: "Properties", href: "/properties" },
  { label: "Agents", href: "/agents" },
  { label: "About", href: "/about" },
  { label: "Contact", href: "/contact" },
];

export default function Navbar() {
  const [open, setOpen] = useState(false);

  return (
    <header className="sticky top-0 z-50 bg-white/95 backdrop-blur border-b border-slate-200">
      <div className="container-x flex h-16 items-center justify-between">
        <Link href="/" className="flex items-center gap-2 shrink-0">
          <span className="flex h-9 w-9 items-center justify-center rounded-lg bg-orange text-white">
            <Home size={18} strokeWidth={2.5} />
          </span>
          <span className="text-lg font-bold tracking-tight text-dark">
            Estate<span className="text-orange">X</span>
          </span>
        </Link>

        <nav className="hidden lg:flex items-center gap-8">
          {navLinks.map((link) => (
            <Link
              key={link.href}
              href={link.href}
              className="text-sm font-medium text-slate-600 hover:text-dark transition-colors"
            >
              {link.label}
            </Link>
          ))}
        </nav>

        <div className="hidden lg:flex items-center gap-3">
          <Link
            href="/login"
            className="text-sm font-medium text-slate-600 hover:text-dark transition-colors px-3 py-2"
          >
            Sign In
          </Link>
          <Link
            href="/register"
            className="text-sm font-semibold text-white bg-orange hover:bg-orange-600 transition-colors px-4 py-2.5 rounded-lg"
          >
            Get Started
          </Link>
        </div>

        <button
          type="button"
          aria-label={open ? "Close menu" : "Open menu"}
          aria-expanded={open}
          onClick={() => setOpen((v) => !v)}
          className="lg:hidden flex h-10 w-10 items-center justify-center rounded-lg text-dark hover:bg-slate-100 transition-colors"
        >
          {open ? <X size={22} /> : <Menu size={22} />}
        </button>
      </div>

      {open && (
        <div className="lg:hidden border-t border-slate-200 bg-white">
          <nav className="container-x flex flex-col py-3">
            {navLinks.map((link) => (
              <Link
                key={link.href}
                href={link.href}
                onClick={() => setOpen(false)}
                className="py-3 text-base font-medium text-slate-700 border-b border-slate-100 last:border-none"
              >
                {link.label}
              </Link>
            ))}
            <div className="flex flex-col gap-3 pt-4 pb-2">
              <Link
                href="/login"
                onClick={() => setOpen(false)}
                className="w-full text-center text-sm font-medium text-slate-700 border border-slate-200 rounded-lg py-3"
              >
                Sign In
              </Link>
              <Link
                href="/register"
                onClick={() => setOpen(false)}
                className="w-full text-center text-sm font-semibold text-white bg-orange rounded-lg py-3"
              >
                Get Started
              </Link>
            </div>
          </nav>
        </div>
      )}
    </header>
  );
}

```

## `components/PropertyCard.tsx`

```tsx
"use client";

import Image from "next/image";
import Link from "next/link";
import { useState } from "react";
import { Bed, Bath, Ruler, Heart, MapPin, ArrowRight } from "lucide-react";
import { Property } from "@/types/property";

export default function PropertyCard({ property }: { property: Property }) {
  const [saved, setSaved] = useState(false);

  return (
    <div className="group rounded-2xl border border-slate-200 bg-white overflow-hidden shadow-card hover:shadow-cardHover transition-shadow duration-300">
      <div className="relative h-56 w-full overflow-hidden">
        <Image
          src={property.image}
          alt={property.title}
          fill
          sizes="(max-width: 768px) 100vw, (max-width: 1200px) 50vw, 33vw"
          className="object-cover group-hover:scale-105 transition-transform duration-500"
        />
        <span className="absolute top-3 left-3 rounded-md bg-white/95 px-2.5 py-1 text-xs font-semibold text-dark shadow-sm">
          {property.listingType}
        </span>
        <button
          type="button"
          aria-label={saved ? "Remove from saved" : "Save property"}
          aria-pressed={saved}
          onClick={() => setSaved((v) => !v)}
          className="absolute top-3 right-3 flex h-9 w-9 items-center justify-center rounded-full bg-white/95 shadow-sm hover:bg-white transition-colors"
        >
          <Heart
            size={17}
            className={saved ? "fill-orange text-orange" : "text-slate-500"}
          />
        </button>
      </div>

      <div className="p-5">
        <div className="flex items-start justify-between gap-3">
          <h3 className="text-base font-semibold text-dark leading-snug">
            {property.title}
          </h3>
        </div>

        <p className="mt-1.5 flex items-center gap-1.5 text-sm text-slate-500">
          <MapPin size={14} />
          {property.location}, {property.city}
        </p>

        <p className="mt-3 text-lg font-bold text-orange">
          {property.priceLabel}
        </p>

        <div className="mt-4 flex items-center gap-4 text-sm text-slate-600 border-t border-slate-100 pt-4">
          <span className="flex items-center gap-1.5">
            <Bed size={16} className="text-slate-400" />
            {property.bedrooms}
          </span>
          <span className="flex items-center gap-1.5">
            <Bath size={16} className="text-slate-400" />
            {property.bathrooms}
          </span>
          <span className="flex items-center gap-1.5">
            <Ruler size={16} className="text-slate-400" />
            {property.area}
          </span>
        </div>

        <Link
          href={`/properties/${property.id}`}
          className="mt-5 flex items-center justify-center gap-1.5 w-full rounded-lg border border-slate-200 py-2.5 text-sm font-semibold text-dark hover:bg-orange hover:text-white hover:border-orange transition-colors"
        >
          View Property
          <ArrowRight size={15} />
        </Link>
      </div>
    </div>
  );
}

```

## `components/PropertySearch.tsx`

```tsx
"use client";

import { useRouter } from "next/navigation";
import { useState, FormEvent } from "react";
import { MapPin, Building2, Tag, Search } from "lucide-react";

const propertyTypes = ["Any Type", "Apartment", "House", "Villa", "Land", "Commercial"];
const purposes = ["Buy", "Rent", "Shortlet"];

export default function PropertySearch({ className = "" }: { className?: string }) {
  const router = useRouter();
  const [location, setLocation] = useState("");
  const [type, setType] = useState(propertyTypes[0]);
  const [purpose, setPurpose] = useState(purposes[0]);

  function handleSubmit(e: FormEvent) {
    e.preventDefault();
    const params = new URLSearchParams();
    if (location.trim()) params.set("location", location.trim());
    if (type !== "Any Type") params.set("type", type);
    params.set("purpose", purpose);
    router.push(`/properties?${params.toString()}`);
  }

  return (
    <form
      onSubmit={handleSubmit}
      className={`bg-white rounded-2xl shadow-cardHover border border-slate-100 p-3 sm:p-4 ${className}`}
    >
      <div className="flex flex-col sm:flex-row gap-3">
        <label className="flex-1 flex items-center gap-2 rounded-xl border border-slate-200 px-3.5 py-3 focus-within:border-orange transition-colors">
          <MapPin size={18} className="text-slate-400 shrink-0" />
          <input
            type="text"
            value={location}
            onChange={(e) => setLocation(e.target.value)}
            placeholder="Location, e.g. Lekki"
            className="w-full text-sm outline-none placeholder:text-slate-400 bg-transparent"
          />
        </label>

        <label className="flex-1 flex items-center gap-2 rounded-xl border border-slate-200 px-3.5 py-3 focus-within:border-orange transition-colors">
          <Building2 size={18} className="text-slate-400 shrink-0" />
          <select
            value={type}
            onChange={(e) => setType(e.target.value)}
            className="w-full text-sm outline-none bg-transparent text-dark"
          >
            {propertyTypes.map((t) => (
              <option key={t} value={t}>
                {t}
              </option>
            ))}
          </select>
        </label>

        <label className="flex-1 flex items-center gap-2 rounded-xl border border-slate-200 px-3.5 py-3 focus-within:border-orange transition-colors">
          <Tag size={18} className="text-slate-400 shrink-0" />
          <select
            value={purpose}
            onChange={(e) => setPurpose(e.target.value)}
            className="w-full text-sm outline-none bg-transparent text-dark"
          >
            {purposes.map((p) => (
              <option key={p} value={p}>
                {p}
              </option>
            ))}
          </select>
        </label>

        <button
          type="submit"
          className="flex items-center justify-center gap-2 rounded-xl bg-orange hover:bg-orange-600 transition-colors text-white text-sm font-semibold px-6 py-3 shrink-0"
        >
          <Search size={17} />
          Search
        </button>
      </div>
    </form>
  );
}

```

## `components/SectionHeading.tsx`

```tsx
type SectionHeadingProps = {
  eyebrow?: string;
  heading: string;
  description?: string;
  align?: "left" | "center";
};

export default function SectionHeading({
  eyebrow,
  heading,
  description,
  align = "left",
}: SectionHeadingProps) {
  return (
    <div className={align === "center" ? "text-center mx-auto max-w-2xl" : ""}>
      {eyebrow && (
        <div
          className={`flex items-center gap-2 mb-3 ${
            align === "center" ? "justify-center" : ""
          }`}
        >
          <span className="h-1.5 w-1.5 rounded-full bg-orange" />
          <span className="text-sm font-semibold text-orange">{eyebrow}</span>
        </div>
      )}
      <h2 className="text-3xl sm:text-4xl font-bold tracking-tight text-dark">
        {heading}
      </h2>
      {description && (
        <p className="mt-3 text-base text-slate-600 leading-relaxed">
          {description}
        </p>
      )}
    </div>
  );
}

```

## `data/properties.ts`

```ts
import { Property } from "@/types/property";

export const properties: Property[] = [
  {
    id: 1,
    title: "Modern Luxury Duplex",
    location: "Lekki Phase 1",
    city: "Lagos",
    price: 85000000,
    priceLabel: "₦85m",
    type: "House",
    listingType: "For Sale",
    bedrooms: 4,
    bathrooms: 5,
    area: "450 sqm",
    image:
      "https://images.unsplash.com/photo-1600585154340-be6161a56a0c?w=1200&q=80",
    description:
      "A striking contemporary duplex set within a gated estate in Lekki Phase 1. Finished to a premium standard with double-height living spaces, a fitted kitchen with imported cabinetry, en-suite bedrooms, a private study, and a landscaped rear garden. Ideal for a family seeking space, security, and easy access to the Lekki-Epe corridor.",
    featured: true,
  },
  {
    id: 2,
    title: "Contemporary Family Home",
    location: "Ikoyi",
    city: "Lagos",
    price: 120000000,
    priceLabel: "₦120m",
    type: "House",
    listingType: "For Sale",
    bedrooms: 5,
    bathrooms: 6,
    area: "600 sqm",
    image:
      "https://images.unsplash.com/photo-1600596542815-ffad4c1539a9?w=1200&q=80",
    description:
      "An expansive five-bedroom home on one of Ikoyi's quiet, tree-lined streets. The residence features a formal dining room, a family lounge opening onto a covered terrace, a home cinema, staff quarters, and a two-car garage. Walking distance to top international schools and the Ikoyi Club.",
    featured: true,
  },
  {
    id: 3,
    title: "Elegant Garden Villa",
    location: "Ajah",
    city: "Lagos",
    price: 65000000,
    priceLabel: "₦65m",
    type: "Villa",
    listingType: "For Sale",
    bedrooms: 4,
    bathrooms: 4,
    area: "500 sqm",
    image:
      "https://images.unsplash.com/photo-1613977257363-707ba9348227?w=1200&q=80",
    description:
      "A serene garden villa in a fast-growing Ajah neighbourhood, offering generous outdoor space, a private swimming pool, and a bright open-plan living and dining area. Close to shopping centres, schools, and the Lekki-Epe expressway, with plenty of room for a growing family.",
    featured: true,
  },
  {
    id: 4,
    title: "Luxury City Apartment",
    location: "Victoria Island",
    city: "Lagos",
    price: 8500000,
    priceLabel: "₦8.5m/year",
    type: "Apartment",
    listingType: "For Rent",
    bedrooms: 3,
    bathrooms: 3,
    area: "220 sqm",
    image:
      "https://images.unsplash.com/photo-1512917774080-9991f1c4c750?w=1200&q=80",
    description:
      "A fully serviced three-bedroom apartment on Victoria Island, moments from major banks, corporate headquarters, and waterfront restaurants. Comes with 24-hour power, a fitted gym, secure parking, and round-the-clock estate security — built for professionals who want city living without compromise.",
    featured: false,
  },
  {
    id: 5,
    title: "Executive Penthouse",
    location: "Banana Island",
    city: "Lagos",
    price: 180000000,
    priceLabel: "₦180m",
    type: "Apartment",
    listingType: "For Sale",
    bedrooms: 4,
    bathrooms: 5,
    area: "520 sqm",
    image:
      "https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?w=1200&q=80",
    description:
      "A statement penthouse on Banana Island with panoramic lagoon views, a private elevator lobby, floor-to-ceiling glazing, and a wraparound terrace built for entertaining. Finished with imported marble, smart-home controls, and access to the estate's private marina.",
    featured: true,
  },
  {
    id: 6,
    title: "Modern Family Apartment",
    location: "Yaba",
    city: "Lagos",
    price: 3500000,
    priceLabel: "₦3.5m/year",
    type: "Apartment",
    listingType: "For Rent",
    bedrooms: 2,
    bathrooms: 2,
    area: "150 sqm",
    image:
      "https://images.unsplash.com/photo-1502672260266-1c1ef2d93688?w=1200&q=80",
    description:
      "A well-maintained two-bedroom apartment in the heart of Yaba, close to tech hubs, universities, and the mainland's busiest transport links. Features a modern kitchen, tiled interiors, and a shared compound with backup power and gated access.",
    featured: false,
  },
];

```

## `next-env.d.ts`

```ts
/// <reference types="next" />
/// <reference types="next/image-types/global" />

// NOTE: This file should not be edited
// see https://nextjs.org/docs/app/building-your-application/configuring/typescript for more information.

```

## `next.config.mjs`

```js
/** @type {import('next').NextConfig} */
const nextConfig = {
  images: {
    remotePatterns: [
      {
        protocol: "https",
        hostname: "images.unsplash.com",
      },
    ],
  },
};

export default nextConfig;

```

## `package.json`

```json
{
  "name": "estate-x",
  "version": "0.1.0",
  "private": true,
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "lint": "next lint"
  },
  "dependencies": {
    "next": "14.2.5",
    "react": "^18.3.1",
    "react-dom": "^18.3.1",
    "lucide-react": "latest"
  },
  "devDependencies": {
    "typescript": "^5.5.4",
    "@types/node": "^20.14.15",
    "@types/react": "^18.3.3",
    "@types/react-dom": "^18.3.0",
    "autoprefixer": "^10.4.19",
    "postcss": "^8.4.40",
    "tailwindcss": "^3.4.7",
    "eslint": "^8.57.0",
    "eslint-config-next": "14.2.5"
  }
}

```

## `postcss.config.js`

```js
module.exports = {
  plugins: {
    tailwindcss: {},
    autoprefixer: {},
  },
};

```

## `tailwind.config.ts`

```ts
import type { Config } from "tailwindcss";

const config: Config = {
  content: [
    "./app/**/*.{ts,tsx}",
    "./components/**/*.{ts,tsx}",
  ],
  theme: {
    extend: {
      colors: {
        orange: {
          DEFAULT: "#f97316",
          50: "#fff7ed",
          100: "#ffedd5",
          200: "#fed7aa",
          300: "#fdba74",
          400: "#fb923c",
          500: "#f97316",
          600: "#ea580c",
          700: "#c2410c",
        },
        dark: "#0f172a",
      },
      fontFamily: {
        sans: [
          "var(--font-sans)",
          "ui-sans-serif",
          "system-ui",
          "-apple-system",
          "Segoe UI",
          "Roboto",
          "Helvetica Neue",
          "Arial",
          "sans-serif",
        ],
      },
      maxWidth: {
        content: "1280px",
      },
      boxShadow: {
        card: "0 1px 2px rgba(15,23,42,0.04), 0 8px 24px rgba(15,23,42,0.06)",
        cardHover: "0 4px 10px rgba(15,23,42,0.06), 0 16px 40px rgba(15,23,42,0.10)",
      },
      borderRadius: {
        xl2: "1.25rem",
      },
    },
  },
  plugins: [],
};

export default config;

```

## `tsconfig.json`

```json
{
  "compilerOptions": {
    "target": "ES2017",
    "lib": ["dom", "dom.iterable", "esnext"],
    "allowJs": true,
    "skipLibCheck": true,
    "strict": true,
    "noEmit": true,
    "esModuleInterop": true,
    "module": "esnext",
    "moduleResolution": "bundler",
    "resolveJsonModule": true,
    "isolatedModules": true,
    "jsx": "preserve",
    "incremental": true,
    "plugins": [{ "name": "next" }],
    "baseUrl": ".",
    "paths": {
      "@/*": ["./*"]
    }
  },
  "include": ["next-env.d.ts", "**/*.ts", "**/*.tsx", ".next/types/**/*.ts"],
  "exclude": ["node_modules"]
}

```

## `types/property.ts`

```ts
export type Property = {
  id: number;
  title: string;
  location: string;
  city: string;
  price: number;
  priceLabel: string;
  type: string;
  listingType: "For Sale" | "For Rent" | "Shortlet";
  bedrooms: number;
  bathrooms: number;
  area: string;
  image: string;
  description: string;
  featured: boolean;
};

```


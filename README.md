<img width="1272" height="788" alt="image" src="https://github.com/user-attachments/assets/7388e31a-42ba-4963-98cb-2231a2678e76" />"use client"

import { Navbar } from "@/components/navbar"
import { Hero } from "@/components/hero"
import { QRGenerator } from "@/components/qr-generator"
import { Features } from "@/components/features"
import { ProSection } from "@/components/pro-section"
import { Testimonials } from "@/components/testimonials"
import { FAQ } from "@/components/faq"
import { Footer } from "@/components/footer"
import { ProProvider } from "@/contexts/pro-context"
import { ProModal } from "@/components/pro-modal"
import { ProWall } from "@/components/pro-wall"

export default function Home() {
  return (
    <ProProvider>
      <main className="min-h-screen bg-background">
      <meta name="google-site-verification" content="BFK38skX6FaTNCH5H1QYEXoNmztTU3jHJ52TNCrHCDM" />
        <Navbar />
        <Hero />
        <QRGenerator />
        <Features />
        <ProSection />
        <Testimonials />
        <ProWall />
        <FAQ />
        <Footer />
        <ProModal />
      </main>
    </ProProvider>
  )
}

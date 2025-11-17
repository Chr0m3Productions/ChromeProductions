# ChromeProductions

import React from "react";
import Gallery from "./components/Gallery";
import BookingForm from "./components/BookingForm";
import "./App.css";

function App() {
  return (
    <div className="App">
      <header>
        <h1>Chrom3 Productions Videography</h1>
        <nav>
          <a href="#showcase">Showcase</a>
          <a href="#booking">Book Me</a>
        </nav>
      </header>
      <main>
        <section id="showcase">
          <h2>My Work</h2>
          <Gallery />
        </section>
        <section id="booking">
          <h2>Book a Session</h2>
          <BookingForm />
        </section>
      </main>
      <footer>
        <small>&copy; 2025 Chrom3 Productions. All Rights Reserved.</small>
      </footer>
    </div>
  );
}

export default App;

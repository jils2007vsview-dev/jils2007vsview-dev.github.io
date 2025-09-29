export default function Portfolio() {
  return (
    <div className="min-h-screen bg-gray-50 text-gray-800">
      {/* Navbar */}
      <nav className="flex justify-between items-center px-8 py-4 shadow-md bg-white">
        <h1 className="text-2xl font-bold text-blue-600">Jilson Johnson</h1>
        <ul className="flex gap-6 text-lg">
          <li><a href="#about" className="hover:text-blue-500">About</a></li>
          <li><a href="#education" className="hover:text-blue-500">Education</a></li>
          <li><a href="#skills" className="hover:text-blue-500">Skills</a></li>
          <li><a href="#projects" className="hover:text-blue-500">Projects</a></li>
          <li><a href="#interests" className="hover:text-blue-500">Interests</a></li>
          <li><a href="#contact" className="hover:text-blue-500">Contact</a></li>
        </ul>
      </nav>

      {/* Hero Section */}
      <section className="flex flex-col items-center justify-center text-center py-20 bg-gradient-to-r from-blue-100 to-blue-200">
        <h2 className="text-4xl font-bold mb-4">Hi, I'm <span className="text-blue-600">Jilson Johnson</span></h2>
        <p className="text-lg max-w-2xl">A student at Rajagiri School of Engineering and Technology, passionate about technology, football, and inspired by Cristiano Ronaldo.</p>
      </section>

      {/* About Section */}
      <section id="about" className="px-8 py-16 max-w-4xl mx-auto">
        <h3 className="text-3xl font-semibold mb-6">About Me</h3>
        <p className="text-lg leading-relaxed">I live in Skyline Ivy League Apartments and my hometown is Kollam. I enjoy learning new things, playing football, and working on exciting projects that help me grow both personally and professionally.</p>
      </section>

      {/* Education Section */}
      <section id="education" className="px-8 py-16 bg-gray-100 max-w-4xl mx-auto">
        <h3 className="text-3xl font-semibold mb-6">Education</h3>
        <div className="bg-white shadow-md rounded-2xl p-6">
          <h4 className="text-xl font-bold">Rajagiri School of Engineering and Technology</h4>
          <p className="text-gray-600">Bachelor of Technology (B.Tech)</p>
        </div>
      </section>

      {/* Skills Section */}
      <section id="skills" className="px-8 py-16 max-w-4xl mx-auto">
        <h3 className="text-3xl font-semibold mb-6">Skills</h3>
        <ul className="grid grid-cols-2 gap-4 text-lg">
          <li>Python 🐍</li>
          <li>C Programming</li>
          <li>Artificial Intelligence & Data Science</li>
          <li>Problem Solving</li>
        </ul>
      </section>

      {/* Projects Section */}
      <section id="projects" className="px-8 py-16 bg-gray-100 max-w-4xl mx-auto">
        <h3 className="text-3xl font-semibold mb-6">Projects</h3>
        <div className="space-y-6">
          <div className="bg-white shadow-md rounded-2xl p-6">
            <h4 className="text-xl font-bold">Weather Data Analyzer</h4>
            <p className="text-gray-600">A tool that processes uploaded weather data files to generate summaries, trends, and visualizations on temperature and precipitation.</p>
          </div>
          <div className="bg-white shadow-md rounded-2xl p-6">
            <h4 className="text-xl font-bold">E-Hospital Management System</h4>
            <p className="text-gray-600">A Python and MySQL based project with features like disease analysis, billing, and patient report generation without web dependency.</p>
          </div>
        </div>
      </section>

      {/* Interests Section */}
      <section id="interests" className="px-8 py-16 max-w-4xl mx-auto">
        <h3 className="text-3xl font-semibold mb-6">Interests</h3>
        <ul className="list-disc list-inside text-lg">
          <li>Football ⚽</li>
          <li>My favourite player: Cristiano Ronaldo 🐐</li>
          <li>Technology and AI 🤖</li>
        </ul>
      </section>

      {/* Contact Section */}
      <section id="contact" className="px-8 py-16 bg-gray-100 max-w-4xl mx-auto">
        <h3 className="text-3xl font-semibold mb-6">Contact</h3>
        <p className="text-lg">You can reach out to me at <a href="mailto:jilson@example.com" className="text-blue-600 underline">jilson@example.com</a></p>
      </section>

      {/* Footer */}
      <footer className="text-center py-6 bg-white shadow-inner">
        <p className="text-gray-600">© {new Date().getFullYear()} Jilson Johnson. All rights reserved.</p>
      </footer>
    </div>
  );
}

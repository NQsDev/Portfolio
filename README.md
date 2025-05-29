import React from "react";

export default function Portfolio() {
  return (
    <div className="min-h-screen bg-gray-900 text-white font-sans">
      {/* Hero Section */}
      <section className="text-center py-20 bg-gradient-to-b from-black to-gray-800">
        <h1 className="text-5xl font-bold mb-4">Hi, I'm NQs</h1>
        <p className="text-xl">Roblox Developer – Scripter | Builder | UI/UX | VFX | GFX | Moderator</p>
      </section>

      {/* About Me */}
      <section className="max-w-4xl mx-auto p-8">
        <h2 className="text-3xl font-semibold mb-4">About Me</h2>
        <p className="text-lg">
          I'm a passionate Roblox developer skilled in scripting, building, UI/UX design,
          VFX, GFX, and community moderation. I bring creativity, efficiency, and team
          spirit to every project I join. Whether it's creating immersive experiences or
          managing a community, I thrive in all aspects of game development. I worked as
          an Artist on the hit game <strong>Blade Ball</strong> and currently serve as a Tester for
          <strong> One Touch</strong>. I'm actively looking for new opportunities to contribute to
          Roblox games — either as a developer or part of a staff team.
        </p>
      </section>

      {/* Skills */}
      <section className="bg-gray-800 p-8">
        <h2 className="text-3xl font-semibold mb-4 text-center">Skills</h2>
        <ul className="grid grid-cols-2 md:grid-cols-3 gap-4 text-center text-lg">
          <li>Scripting (Lua)</li>
          <li>Building</li>
          <li>UI/UX Design</li>
          <li>VFX / GFX</li>
          <li>Moderation</li>
          <li>Team Leadership</li>
        </ul>
      </section>

      {/* Projects */}
      <section className="max-w-4xl mx-auto p-8">
        <h2 className="text-3xl font-semibold mb-6">Projects</h2>
        <div className="space-y-6">
          <div className="bg-gray-700 p-4 rounded-xl shadow-md">
            <h3 className="text-2xl font-bold">Blade Ball</h3>
            <p className="text-sm italic mb-2">Role: Artist</p>
            <p>Contributed visual assets and effects for the popular Roblox game Blade Ball, helping bring its fast-paced gameplay to life with high-quality graphics.</p>
          </div>

          <div className="bg-gray-700 p-4 rounded-xl shadow-md">
            <h3 className="text-2xl font-bold">One Touch</h3>
            <p className="text-sm italic mb-2">Role: Tester</p>
            <p>Currently testing and providing feedback for gameplay, bugs, and user experience improvements to support a smooth and balanced player experience.</p>
          </div>

          {/* Add more project blocks as needed */}
        </div>
      </section>

      {/* Contact */}
      <section className="bg-gray-800 p-8 text-center">
        <h2 className="text-3xl font-semibold mb-4">Contact</h2>
        <p className="text-lg">Discord: nqsdev</p>
        <p className="text-lg">Email: bidobidoswg@gmail.com</p>
      </section>
    </div>
  );
}


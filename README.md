export default function Home() {
  return (
    <div className="min-h-screen bg-[#F5F5F5] flex flex-col items-center justify-center">
      <nav className="bg-[#075AAA] w-full py-4 px-6 flex justify-between items-center">
        <span className="text-white font-bold text-xl">British Airways PTFS</span>
        <div className="space-x-6">
          <a href="#" className="text-white hover:text-[#E41F28]">Home</a>
          <a href="#" className="text-white hover:text-[#E41F28]">About</a>
          <a href="#" className="text-white hover:text-[#E41F28]">Training</a>
          <a href="#" className="text-white hover:text-[#E41F28]">Contact</a>
        </div>
      </nav>
      <main className="flex-1 flex flex-col items-center justify-center">
        <div className="bg-white rounded-lg shadow p-8 text-center">
          <h1 className="text-4xl font-bold text-[#075AAA] mb-4">Welcome to British Airways PTFS</h1>
          <p className="mb-6 text-gray-700">
            Take off on your pilot journey! This site is dedicated to British Airways pilots and PTFS fans.
          </p>
          <img
            src="https://upload.wikimedia.org/wikipedia/commons/6/6c/British_Airways_Logo.png"
            alt="British Airways Logo"
            className="mx-auto w-48 mb-6"
          />
          <a href="#" className="px-6 py-3 bg-[#075AAA] text-white font-semibold rounded hover:bg-[#E41F28] transition-colors">
            Start Training
          </a>
        </div>
      </main>
      <footer className="py-4 text-gray-500 text-sm text-center w-full">
        &copy; {new Date().getFullYear()} British Airways PTFS | Fan project, not affiliated with British Airways or Roblox.
      </footer>
    </div>
  );
}

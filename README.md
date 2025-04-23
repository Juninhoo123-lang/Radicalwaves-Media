export default function Home() {
  return (
    <main className="min-h-screen bg-black text-white font-sans">
      <section className="text-center py-20 px-4">
        <h1 className="text-5xl font-bold text-cyan-400 mb-4">RADICALWAVES</h1>
        <p className="text-xl text-gray-300 max-w-2xl mx-auto">
          Agência criativa de audiovisual especializada em eventos, conteúdo e redes sociais. Levamos sua ideia a outro nível.
        </p>
      </section>

      <section className="grid md:grid-cols-2 lg:grid-cols-3 gap-6 px-6 pb-20">
        <div className="bg-zinc-900 p-6 rounded-2xl shadow-xl">
          <h2 className="text-2xl font-bold text-cyan-300 mb-2">🎥 Produção de Vídeo</h2>
          <p>Captação, edição e entrega de vídeos profissionais para eventos e marcas.</p>
        </div>
        <div className="bg-zinc-900 p-6 rounded-2xl shadow-xl">
          <h2 className="text-2xl font-bold text-cyan-300 mb-2">📸 Fotografia</h2>
          <p>Fotos criativas e com alta qualidade para portfólios, produtos e bastidores.</p>
        </div>
        <div className="bg-zinc-900 p-6 rounded-2xl shadow-xl">
          <h2 className="text-2xl font-bold text-cyan-300 mb-2">📱 Redes Sociais</h2>
          <p>Criação de conteúdo visual, reels, stories e gerenciamento de publicações.</p>
        </div>
        <div className="bg-zinc-900 p-6 rounded-2xl shadow-xl">
          <h2 className="text-2xl font-bold text-cyan-300 mb-2">🎫 Cobertura de Eventos</h2>
          <p>Concertos, conferências, cultos e muito mais com cobertura profissional em tempo real.</p>
        </div>
        <div className="bg-zinc-900 p-6 rounded-2xl shadow-xl">
          <h2 className="text-2xl font-bold text-cyan-300 mb-2">💼 Portfólio</h2>
          <p>Veja nossos trabalhos anteriores em vídeo e fotografia. (Em breve galeria interativa)</p>
        </div>
        <div className="bg-zinc-900 p-6 rounded-2xl shadow-xl">
          <h2 className="text-2xl font-bold text-cyan-300 mb-2">💬 Contato</h2>
          <p>Email: <a href="mailto:jsaffss99@gmail.com" className="text-cyan-400 underline">jsaffss99@gmail.com</a><br/>
          WhatsApp: <a href="https://wa.me/258875916367" className="text-cyan-400 underline">+258 875 916 367</a></p>
        </div>
      </section>

      <section className="bg-zinc-800 py-12 px-6">
        <h2 className="text-3xl font-bold text-center text-cyan-400 mb-6">📦 Pacotes e Preços</h2>
        <div className="grid md:grid-cols-3 gap-6">
          <div className="bg-zinc-900 p-6 rounded-2xl shadow-lg">
            <h3 className="text-xl font-bold mb-2">Pacote Básico</h3>
            <p>1 vídeo + 10 fotos <br/> Edição simples <br/> Ideal para redes sociais</p>
            <p className="mt-4 font-bold text-cyan-300">A partir de MZN 2.500</p>
          </div>
          <div className="bg-zinc-900 p-6 rounded-2xl shadow-lg">
            <h3 className="text-xl font-bold mb-2">Pacote Intermediário</h3>
            <p>2 vídeos + 20 fotos <br/> Edição avançada <br/> Conteúdo para uma semana</p>
            <p className="mt-4 font-bold text-cyan-300">A partir de MZN 5.000</p>
          </div>
          <div className="bg-zinc-900 p-6 rounded-2xl shadow-lg">
            <h3 className="text-xl font-bold mb-2">Pacote Profissional</h3>
            <p>Vídeos ilimitados + 50 fotos <br/> Cobertura de evento completo <br/> Gestão de redes sociais</p>
            <p className="mt-4 font-bold text-cyan-300">Sob consulta</p>
          </div>
        </div>
      </section>

      <footer className="text-center py-10 text-gray-500">
        © 2025 RADICALWAVES — Todos os direitos reservados
      </footer>
    </main>
  );
}

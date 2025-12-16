import React, { useState, useEffect, useRef } from 'react';
import { Play, Pause, RotateCcw, Eye, EyeOff, Shuffle, Palette, Clock, MapPin, Film, Zap, Monitor, Box, Dog, Brain, Music, Globe } from 'lucide-react';

const PictionaryGame = () => {
  // Banco de Dados Expandido
  const gameData = {
    "Animais": {
      words: [
        "Girafa", "Elefante", "Pinguim", "Leão", "Cachorro", "Gato", "Tartaruga", "Coelho",
        "Sapo", "Borboleta", "Tubarão", "Baleia", "Cavalo", "Vaca", "Porco",
        "Ornitorrinco", "Camaleão", "Suricato", "Lhama", "Tatu", "Preguiça", "Água-viva",
        "Polvo", "Tamanduá", "Hiena", "Avestruz", "Pavão", "Canguru", "Lêmure",
        "Narval", "Axolote", "Capivara", "Equidna", "Panda Vermelho", "Dragão de Komodo"
      ],
      color: "bg-red-400",
      icon: <Dog className="w-5 h-5 text-white" />
    },
    "Objetos": {
      words: [
        "Liquidificador", "Abajur", "Sofá", "Geladeira", "Microondas", "Vassoura", "Espelho",
        "Cama", "Travesseiro", "Chuveiro", "Torneira", "Escada", "Tapete",
        "Guarda-chuva", "Saca-rolhas", "Grampeador", "Telescópio", "Bumerangue", "Cofre",
        "Dicionário", "Zíper", "Ambulância", "Piano", "Violão", "Bateria", "Anzol",
        "Bússola", "Capacete", "Extintor", "Binóculos", "Paraquedas", "Seringa"
      ],
      color: "bg-amber-400",
      icon: <Box className="w-5 h-5 text-white" />
    },
    "Ações": {
      words: [
        "Espirrar", "Mergulhar", "Costurar", "Acampar", "Tricotar", "Sussurrar", "Escalar",
        "Cozinhar", "Pesar", "Equilibrar", "Meditar", "Jardinar", "Esquiar", "Investigar",
        "Pintar", "Dançar", "Cantar", "Chorar", "Rir", "Bocejar", "Vomitar",
        "Dirigir", "Pescar", "Surfar", "Cavar", "Plantar", "Varre", "Passar roupa",
        "Tossir", "Espreguiçar", "Mancar", "Aplaudir", "Abraçar"
      ],
      color: "bg-emerald-400",
      icon: <Zap className="w-5 h-5 text-white" />
    },
    "TI (Iniciante)": {
      words: [
        // Hardware & Periféricos
        "Computador", "Mouse", "Teclado", "Monitor", "Notebook", "Celular", "Tablet",
        "Cabo USB", "Pendrive", "Fone de Ouvido", "Impressora", "Roteador", "Webcam",
        "Microfone", "Botão Power", "Mousepad", "Joystick", "Placa Mãe", "Processador",
        // Software & Interface
        "Janela", "Ícone", "Lixeira", "Pasta", "Arquivo", "Cursor", "Barra de Carregamento",
        "Tela Azul", "Google", "YouTube", "WhatsApp", "Instagram", "Facebook",
        // Conceitos & Rede
        "Wi-Fi", "Bluetooth", "Internet", "Nuvem", "Senha", "E-mail", "Arroba",
        "Download", "Upload", "Link", "PDF", "Vírus", "Antivírus",
        // Cultura Dev
        "Robô", "Hacker", "Bug", "Código", "Programador", "Binário (01)", "Gamer",
        "Pixel", "Emoji", "Backup", "Algoritmo", "Python"
      ],
      color: "bg-blue-500",
      icon: <Monitor className="w-5 h-5 text-white" />
    },
    "Lugares": {
      words: [
        "Deserto", "Biblioteca", "Circo", "Cemitério", "Aeroporto", "Padaria",
        "Fundo do Mar", "Lua", "Castelo", "Laboratório", "Caverna", "Estádio",
        "Museu", "Farol", "Hospital", "Escola", "Praia", "Floresta", "Montanha",
        "Cinema", "Shopping", "Zoológico", "Parque", "Igreja", "Restaurante",
        "Banco", "Correio", "Delegacia", "Bombeiros", "Hotel", "Pirâmides"
      ],
      color: "bg-indigo-400",
      icon: <MapPin className="w-5 h-5 text-white" />
    },
    "Difícil/Abstrato": {
      words: [
        "Saudade", "Futuro", "Silêncio", "Gravidade", "Eletricidade", "Internet",
        "Sonho", "Pesadelo", "Ideia", "Sorte", "Liberdade", "Caos", "Segredo",
        "Vento", "Amor", "Ódio", "Paz", "Guerra", "Tempo", "Música", "Alma",
        "Fome", "Sede", "Calor", "Frio", "Medo", "Coragem", "Mentira", "Verdade",
        "Ciúmes", "Inveja", "Esperança", "Fé", "Democracia", "Justiça"
      ],
      color: "bg-pink-400",
      icon: <Brain className="w-5 h-5 text-white" />
    },
    "Cultura Pop": {
      words: [
        "Harry Potter", "Homem-Aranha", "Shrek", "Titanic", "Star Wars", "Batman",
        "Barbie", "Matrix", "O Rei Leão", "Frozen", "Mario Bros", "Pikachu",
        "Sherlock Holmes", "Drácula", "Mickey Mouse", "Bob Esponja", "Simpsons",
        "Vingadores", "Senhor dos Anéis", "De Volta para o Futuro", "Jurassic Park",
        "Minions", "Sonic", "Mulher Maravilha", "Coringa", "Darth Vader", "Yoda"
      ],
      color: "bg-violet-400",
      icon: <Film className="w-5 h-5 text-white" />
    },
    "Profissões": {
      words: [
        "Médico", "Professor", "Bombeiro", "Policial", "Astronauta", "Bailarina",
        "Palhaço", "Mágico", "Cozinheiro", "Jardineiro", "Pintor", "Mecânico",
        "Juiz", "Advogado", "Dentista", "Veterinário", "Piloto", "Marinheiro",
        "Detetive", "Arqueólogo", "Cientista", "Fotógrafo", "Jornalista"
      ],
      color: "bg-cyan-600",
      icon: <Globe className="w-5 h-5 text-white" />
    }
  };

  const categories = Object.keys(gameData);

  // Estados do Jogo
  const [currentCategory, setCurrentCategory] = useState(null);
  const [currentWord, setCurrentWord] = useState(null);
  const [isRevealed, setIsRevealed] = useState(false);
  const [selectedFilter, setSelectedFilter] = useState('Todas');
  
  // Estado para controlar palavras já usadas (Histórico)
  const [usedWords, setUsedWords] = useState({});

  // Estados da Roleta e Animação
  const [rotation, setRotation] = useState(0);
  const [isSpinning, setIsSpinning] = useState(false);
  const [isFullScreen, setIsFullScreen] = useState(false); // Novo: Controla expansão
  const [showCategoryResult, setShowCategoryResult] = useState(false); // Novo: Controla animação da categoria
  const [tempCategory, setTempCategory] = useState(null); // Novo: Categoria temporária para exibição

  // Estados do Cronômetro
  const [timeLeft, setTimeLeft] = useState(60);
  const [isRunning, setIsRunning] = useState(false);
  const timerRef = useRef(null);

  // Lógica do Cronômetro
  useEffect(() => {
    if (isRunning && timeLeft > 0) {
      timerRef.current = setTimeout(() => {
        setTimeLeft(timeLeft - 1);
      }, 1000);
    } else if (timeLeft === 0) {
      setIsRunning(false);
    }
    return () => clearTimeout(timerRef.current);
  }, [isRunning, timeLeft]);

  const toggleTimer = () => setIsRunning(!isRunning);
  
  const resetTimer = () => {
    setIsRunning(false);
    setTimeLeft(60);
  };

  // Lógica de Sorteio com Roleta
  const handleSpin = () => {
    if (isSpinning) return;
    
    // Resetar estado visual
    setIsRevealed(false);
    setCurrentWord(null);
    setCurrentCategory(null);
    setShowCategoryResult(false);
    
    // Iniciar sequência
    setIsFullScreen(true); // Expande a roleta
    setIsSpinning(true);
    resetTimer();

    // Determinar categoria alvo
    let targetCat = selectedFilter;
    if (selectedFilter === 'Todas') {
      const randomIndex = Math.floor(Math.random() * categories.length);
      targetCat = categories[randomIndex];
    }

    // Calcular rotação
    const segmentSize = 360 / categories.length;
    const targetIndex = categories.indexOf(targetCat);
    const randomOffset = Math.floor(Math.random() * (segmentSize - 10)) + 5; 
    
    // Rotação: 2160 (6 voltas) + ajuste para parar no segmento certo
    const targetRotation = 2160 + (360 - (targetIndex * segmentSize)) - (segmentSize / 2) + randomOffset;
    
    setRotation(prev => prev + targetRotation);

    // Sequência de Animação
    // 1. A roleta gira por 3 segundos
    setTimeout(() => {
      setIsSpinning(false);
      setTempCategory(targetCat); // Define categoria para mostrar na animação
      setShowCategoryResult(true); // Dispara animação do nome da categoria

      // 2. O nome da categoria fica na tela por 2.5 segundos
      setTimeout(() => {
        // 3. Volta ao normal e sorteia a palavra
        setIsFullScreen(false);
        setShowCategoryResult(false);
        selectWord(targetCat); 
      }, 2500);

    }, 3000);
  };

  const selectWord = (category) => {
    const wordsList = gameData[category].words;
    
    // Recupera palavras já usadas desta categoria (ou array vazio)
    let categoryUsed = usedWords[category] || [];
    
    // Filtra palavras disponíveis
    let availableWords = wordsList.filter(word => !categoryUsed.includes(word));
    
    // Se todas as palavras já foram usadas, reseta o histórico
    if (availableWords.length === 0) {
      availableWords = wordsList;
      categoryUsed = []; 
    }

    // Sorteia uma das palavras disponíveis
    const randomWord = availableWords[Math.floor(Math.random() * availableWords.length)];
    
    setCurrentCategory(category);
    setCurrentWord(randomWord);
    
    // Atualiza o histórico de palavras usadas
    setUsedWords(prev => ({
      ...prev,
      [category]: [...categoryUsed, randomWord]
    }));
  };

  const formatTime = (seconds) => {
    const mins = Math.floor(seconds / 60);
    const secs = seconds % 60;
    return `${mins}:${secs < 10 ? '0' : ''}${secs}`;
  };

  return (
    <div className="min-h-screen bg-slate-100 font-sans text-slate-800 flex flex-col items-center py-4 px-4 overflow-hidden">
      
      {/* Header */}
      <header className="mb-4 text-center relative z-10">
        <div className="flex items-center justify-center gap-2 mb-1">
          <Palette className="w-8 h-8 text-indigo-600" />
          <h1 className="text-3xl font-extrabold text-indigo-900 tracking-tight">Pictonary</h1>
        </div>
      </header>

      <div className="max-w-md w-full space-y-4">
        
        {/* Controles Superiores */}
        <div className="bg-white p-3 rounded-xl shadow-sm border border-slate-200 flex justify-between items-center relative z-10">
          <label className="text-xs font-bold text-slate-400 uppercase mr-2">
            Modo:
          </label>
          <select 
            value={selectedFilter}
            onChange={(e) => setSelectedFilter(e.target.value)}
            disabled={isSpinning || isFullScreen}
            className="flex-1 p-2 bg-slate-50 border border-slate-200 rounded-lg text-sm font-medium text-slate-700 disabled:opacity-50"
          >
            <option value="Todas">🎲 Roleta (Todas)</option>
            {categories.map(cat => (
              <option key={cat} value={cat}>{cat}</option>
            ))}
          </select>
        </div>

        {/* Área da Roleta - Wrapper para reservar espaço e controlar FullScreen */}
        <div className="h-72 w-full relative flex items-center justify-center z-20">
          
          <div className={
            isFullScreen 
              ? "fixed inset-0 z-50 flex flex-col items-center justify-center bg-slate-900/95 backdrop-blur-md transition-all duration-500 ease-in-out" 
              : "absolute inset-0 flex items-center justify-center transition-all duration-500 ease-in-out"
            }
          >
            {/* Container da Roleta com Escala Dinâmica */}
            <div className={`relative transition-all duration-700 ease-out ${isFullScreen ? 'scale-150 md:scale-[2.0]' : 'scale-100'}`}>
              
              {/* Indicador (Seta) - Move junto com a roleta */}
              <div className="absolute -top-6 left-1/2 -translate-x-1/2 z-20">
                <div className="w-0 h-0 border-l-[15px] border-l-transparent border-r-[15px] border-r-transparent border-t-[25px] border-t-slate-800 drop-shadow-lg"></div>
              </div>

              {/* O Círculo da Roleta */}
              <div 
                className="w-64 h-64 rounded-full shadow-2xl border-4 border-white relative transition-transform duration-[3000ms] cubic-bezier(0.2, 0.8, 0.2, 1)"
                style={{ 
                  transform: `rotate(${rotation}deg)`,
                }}
              >
                {categories.map((cat, index) => {
                  const rotationDeg = (360 / categories.length) * index;
                  const halfSlice = 360 / categories.length / 2;

                  return (
                    <div 
                      key={cat}
                      className="absolute w-full h-full top-0 left-0"
                      style={{ 
                        transform: `rotate(${rotationDeg}deg)`,
                      }}
                    >
                      {/* Linha Divisória */}
                      <div 
                        className={`absolute top-0 left-1/2 -translate-x-1/2 w-[1px] h-1/2 origin-bottom bg-white/40`}
                      ></div>
                      
                      {/* Conteúdo da Fatia */}
                      <div 
                        className="absolute top-0 left-1/2 -translate-x-1/2 h-1/2 origin-bottom pt-6 flex flex-col items-center justify-start"
                        style={{
                            transform: `rotate(${halfSlice}deg)`,
                            width: '4rem'
                        }}
                      >
                        <div className={`p-2 rounded-full bg-white/20 shadow-sm backdrop-blur-md`}>
                          {React.cloneElement(gameData[cat].icon, { className: "w-6 h-6 text-white" })}
                        </div>
                      </div>
                    </div>
                  );
                })}
                
                {/* Background Gradient */}
                <div 
                  className="absolute inset-0 rounded-full -z-10"
                  style={{
                    background: `conic-gradient(
                      #F87171 0deg 45deg, 
                      #FBBF24 45deg 90deg, 
                      #34D399 90deg 135deg, 
                      #3B82F6 135deg 180deg, 
                      #818CF8 180deg 225deg, 
                      #F472B6 225deg 270deg, 
                      #A78BFA 270deg 315deg,
                      #0891B2 315deg 360deg
                    )`
                  }}
                ></div>
                
                {/* Centro da Roleta */}
                <div className="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-8 h-8 bg-white rounded-full shadow-lg border-2 border-slate-200 z-10 flex items-center justify-center">
                  <div className="w-2 h-2 bg-slate-300 rounded-full"></div>
                </div>
              </div>
            </div>

            {/* Animação da Categoria Vencedora (Overlay) */}
            {isFullScreen && showCategoryResult && tempCategory && (
              <div className="absolute inset-0 flex flex-col items-center justify-center z-50 animate-in fade-in zoom-in slide-in-from-bottom-10 duration-500">
                <div className={`p-6 rounded-3xl ${gameData[tempCategory].color} shadow-[0_0_50px_rgba(0,0,0,0.5)] transform scale-125 md:scale-150 flex flex-col items-center gap-4 border-4 border-white`}>
                  <div className="p-3 bg-white/20 rounded-full backdrop-blur-sm">
                    {React.cloneElement(gameData[tempCategory].icon, { className: "w-12 h-12 text-white" })}
                  </div>
                  <h2 className="text-3xl md:text-4xl font-black text-white uppercase tracking-widest drop-shadow-md text-center max-w-[200px] leading-tight">
                    {tempCategory}
                  </h2>
                </div>
                <p className="text-white/80 font-bold mt-8 text-lg animate-pulse">Preparando palavra...</p>
              </div>
            )}

          </div>
        </div>

        {/* Botão de Girar */}
        <button 
          onClick={handleSpin}
          disabled={isSpinning || isFullScreen}
          className="w-full bg-slate-800 hover:bg-slate-900 text-white font-bold py-4 text-lg rounded-xl shadow-lg transition-all active:scale-95 disabled:opacity-50 disabled:cursor-not-allowed flex items-center justify-center gap-2 relative z-10"
        >
          {isSpinning ? (
            <>Sorteando...</>
          ) : (
            <>
              <RotateCcw className="w-5 h-5" />
              GIRAR ROLETA
            </>
          )}
        </button>

        {/* Resultado Final (Palavra) */}
        <div className={`transition-all duration-700 ${currentWord ? 'opacity-100 translate-y-0' : 'opacity-0 translate-y-8 h-0 overflow-hidden'}`}>
          <div className={`bg-white rounded-2xl shadow-xl overflow-hidden border-2 ${currentCategory ? gameData[currentCategory].color.replace('bg-', 'border-') : 'border-slate-200'} relative`}>
            
            <div className={`h-3 w-full ${currentCategory ? gameData[currentCategory].color : 'bg-slate-200'}`}></div>

            <div className="p-6 text-center">
              
              {/* Badge da Categoria (Pequeno, já que o grande apareceu na animação) */}
              <div className="flex items-center justify-center gap-2 mb-4">
                 <span className={`inline-flex items-center gap-1 px-3 py-1 rounded-full text-white text-sm font-bold tracking-wide ${currentCategory ? gameData[currentCategory].color : 'bg-slate-400'}`}>
                  {currentCategory && gameData[currentCategory].icon}
                  {currentCategory?.toUpperCase()}
                </span>
              </div>

              <div className="relative w-full flex justify-center items-center mb-4">
                {isRevealed ? (
                  <h2 className="text-3xl md:text-4xl font-black text-slate-800 break-words animate-in fade-in zoom-in duration-300 leading-tight">
                    {currentWord}
                  </h2>
                ) : (
                  <div 
                    onClick={() => setIsRevealed(true)}
                    className="cursor-pointer bg-slate-50 border-2 border-dashed border-slate-300 rounded-xl p-6 w-full flex flex-col items-center justify-center hover:bg-slate-100 transition-colors group min-h-[120px]"
                  >
                    <Eye className="w-8 h-8 text-slate-400 mb-2 group-hover:text-indigo-500 transition-colors" />
                    <span className="text-slate-500 font-bold text-sm">Toque para ver a palavra</span>
                  </div>
                )}
              </div>

              {isRevealed && (
                <button 
                  onClick={() => setIsRevealed(false)}
                  className="text-slate-400 hover:text-indigo-600 text-xs flex items-center justify-center gap-1 mx-auto"
                >
                  <EyeOff className="w-3 h-3" /> Esconder novamente
                </button>
              )}
            </div>
          </div>
        </div>

        {/* Cronômetro Compacto */}
        <div className="bg-slate-800 rounded-xl p-4 text-white shadow-lg flex items-center justify-between relative z-10">
          <div className="flex items-center gap-3">
            <Clock className={`w-5 h-5 ${isRunning ? 'text-green-400 animate-pulse' : 'text-slate-400'}`} />
            <div className="font-mono text-2xl font-bold tracking-widest leading-none">
              {formatTime(timeLeft)}
            </div>
          </div>

          <div className="flex gap-2">
            <button 
              onClick={toggleTimer}
              className={`p-2 rounded-lg transition-all ${
                isRunning 
                  ? 'bg-red-500/20 text-red-400 hover:bg-red-500/30' 
                  : 'bg-green-500/20 text-green-400 hover:bg-green-500/30'
              }`}
            >
              {isRunning ? <Pause className="w-5 h-5" /> : <Play className="w-5 h-5" />}
            </button>
            <button 
              onClick={resetTimer}
              className="p-2 rounded-lg bg-slate-700 text-slate-300 hover:bg-slate-600 hover:text-white transition-all"
            >
              <RotateCcw className="w-5 h-5" />
            </button>
          </div>
        </div>

      </div>
    </div>
  );
};

export default PictionaryGame;

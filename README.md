<!-- Header -->
<header class="border-b border-slate-800 bg-slate-900/80 backdrop-blur px-8 py-4 flex justify-between items-center shadow-md">
    <div class="flex items-center gap-3">
        <span class="bg-indigo-600 text-white font-bold px-3 py-1.5 rounded-lg text-sm shadow-lg shadow-indigo-600/30">CodeDuel ⚡</span>
        <span class="text-slate-400 text-sm font-medium hidden sm:inline">Algorithmic Battle Arena</span>
    </div>
    <div id="timer" class="bg-red-500/10 text-red-400 border border-red-500/20 px-4 py-1.5 rounded-full font-mono text-sm font-bold">
        Time Left: 02:00
    </div>
</header>

<!-- Main Content -->
<main class="max-w-6xl mx-auto px-6 py-10 grid grid-cols-1 md:grid-cols-2 gap-8 w-full flex-grow items-start">
    
    <!-- Problem Description Card -->
    <div class="bg-slate-900 border border-slate-800 rounded-2xl p-6 shadow-2xl flex flex-col justify-between h-full">
        <div>
            <div class="flex justify-between items-center mb-4">
                <h2 class="text-xl font-bold text-indigo-400">Challenge #1: Reverse String</h2>
                <span class="bg-amber-500/10 text-amber-400 text-xs px-2.5 py-1 rounded-md border border-amber-500/20 font-mono">Easy</span>
            </div>
            <p class="text-slate-300 text-sm leading-relaxed mb-6">
                Write a function that takes a string as input and returns the string reversed.
            </p>
            <div class="bg-slate-950 p-4 rounded-xl border border-slate-800 font-mono text-xs text-slate-400 shadow-inner">
                <p class="text-indigo-300 mb-1 font-semibold">Example:</p>
                <p class="text-slate-200">Input: "Ghada"</p>
                <p class="text-slate-200">Output: "adahG"</p>
            </div>
        </div>
        <div class="mt-8 text-xs text-slate-500 font-mono border-t border-slate-800/60 pt-4">
            Supported Languages: JavaScript, Python, PHP
        </div>
    </div>

    <!-- Code Editor Card -->
    <div class="bg-slate-900 border border-slate-800 rounded-2xl p-6 shadow-2xl flex flex-col justify-between h-full">
        <div class="flex flex-col h-full">
            <div class="flex justify-between items-center mb-3">
                <label class="text-sm font-medium text-slate-300">Code Editor:</label>
                <span class="text-xs text-indigo-400 font-mono bg-indigo-950/50 px-2 py-0.5 rounded border border-indigo-800/50">JavaScript</span>
            </div>
            <textarea class="w-full bg-slate-950 border border-slate-800 rounded-xl p-4 font-mono text-sm text-emerald-400 focus:outline-none focus:border-indigo-500 resize-none h-48 shadow-inner" placeholder="Write your solution here...&#10;function reverseString(str) {&#10;    // Your code goes here&#10;}"></textarea>
            <button onclick="submitCode()" class="mt-6 w-full bg-indigo-600 hover:bg-indigo-500 text-white font-semibold py-3 rounded-xl transition duration-200 shadow-lg shadow-indigo-600/30 cursor-pointer">
                Submit Solution 🚀
            </button>
        </div>
    </div>

</main>

<!-- Footer -->
<footer class="text-center py-6 text-slate-500 text-xs border-t border-slate-800 bg-slate-900/30">
    Developed by Ghada 💻 | CodeDuel Arena
</footer>

<script>
    function submitCode() {
        alert('Solution submitted successfully! Verifying output...');
    }
</script>

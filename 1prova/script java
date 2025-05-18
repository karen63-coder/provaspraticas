document.addEventListener('DOMContentLoaded', () => {
const textArea = document.getElementById('text-area');
const charCountSpan = document.getElementById('char-count');
const wordCountSpan = document.getElementById('word-count');
const yourName = document.getElementById('your-name');


    function addYourName(){
        yourName.textContent ='Nome do Aluno'
    }
    addYourName();

    textArea.addEventListener('input', () => {    
        const text = textArea.value;
        
        const characterCount = text.length;
        charCountSpan.textContent = characterCount;

        const words = text.split(" ");

        const filteredWords = words.filter(word => word.length > 0);

        const wordCount = filteredWords.length;

        wordCountSpan.textContent = wordCount;
    });
});



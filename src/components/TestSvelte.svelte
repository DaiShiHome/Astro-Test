<script>
    let word = '';
  </script>
  
<main>
<label for="wordInput">Enter a word:</label>
<input id="wordInput" type="text" bind:value={word} />

<p>The word you entered is: {word}</p>
</main>

<style>
main {
    font-family: Arial, sans-serif;
    padding: 20px;
}

label {
    margin-right: 10px;
}

input {
    padding: 5px;
    font-size: 16px;
}

p {
    margin-top: 20px;
    font-size: 18px;
}
</style>
  
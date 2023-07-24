# TextChat_fakeMsg
# How to test: enter in console this code and press Enter and then type  any msg in chat

  fetch('https://raw.githubusercontent.com/anvlasov/TextChat_fakeMsg/main/MathExpressions.md')
      .then(response => {
        return response.text();
      })
      .then(response => {
        var output = document.getElementById('output');
        window.fakeMsg = {text: response};
          console.info('Msg was set');

      })

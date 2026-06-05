(function injectSecurely() {
    // 1. Cole seu texto aqui dentro das CRASES
    const textoBruto = ``;

    // 2. LIMPEZA: Remove quebras de linha e espaços duplos
    const textoFinal = textoBruto.replace(/\s+/g, ' ').trim();

    const el = document.querySelector('textarea[placeholder="Responder"]');

    if (el) {
        // Bypass do React State
        const setter = Object.getOwnPropertyDescriptor(window.HTMLTextAreaElement.prototype, "value").set;
        setter.call(el, textoFinal);

        // Notifica o sistema
        el.dispatchEvent(new Event('input', { bubbles: true }));
        el.dispatchEvent(new Event('change', { bubbles: true }));
        
        console.log("Texto limpo e injetado!");
    }
})();

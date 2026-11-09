class KauaCasella:

    # ── Stack ─────────────────────────
    languages  = ["Python", "JavaScript", "C#"]
    web        = ["HTML5", "CSS3"]
    databases  = ["MySQL"]
    tools      = ["Figma", "Unity"]

    # ── Sobre mim ─────────────────────
    graduacao  = "🎓 Ciência da Computação — FECAP"
    interesse  = "💻 Estágio em TI"
    aprendendo = "📚 MySQL e back-end"
    objetivo   = ("🚀 Atuar na área de Dados:"
                  " análise, organização e"
                  " tratamento de informações")
    fora_do_pc = "🏋️ academia · 🤾 handebol · 🎯 FPS"

    def __str__(self) -> str:
        return (
            f"{self.interesse}\n"
            f"{self.objetivo}\n"
            f"> Código é treino."
        )

print(KauaCasella())

# 🤝 Contribuire a Flux

Grazie per il tuo interesse nel contribuire a Flux! Ogni contributo è benvenuto. 🎉

## 📋 Codice di Condotta

Questo progetto segue standard di rispetto e inclusività. Sii gentile e professionale.

## 🚀 Come Contribuire

### 🐛 Segnalare Bug

1. **Controlla** se il bug è già stato segnalato negli [Issues](https://github.com/profpaul001/flux/issues)
2. **Apri un nuovo issue** usando il template per bug report
3. **Fornisci informazioni complete**:
   - Versione di Flux
   - Versione di Python
   - Sistema operativo
   - Passi per riprodurre il bug
   - Comportamento atteso vs attuale

### 💡 Proporre Funzionalità

1. **Apri una discussione** in [Discussions](https://github.com/profpaul001/flux/discussions)
2. **Spiega il caso d'uso** e i benefici
3. **Discuti l'implementazione** con la community
4. **Crea un issue** se la proposta viene accettata

### 🔧 Contribuire con Codice

#### Setup Ambiente di Sviluppo

```bash
# 1. Fork il repository su GitHub
# 2. Clone il tuo fork
git clone https://github.com/TUO-USERNAME/flux.git
cd flux

# 3. Crea virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
# oppure
venv\Scripts\activate     # Windows

# 4. Installa in modalità sviluppo
pip install -e ".[dev]"

# 5. Installa pre-commit hooks
pre-commit install

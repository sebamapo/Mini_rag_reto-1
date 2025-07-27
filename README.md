Dependencias: openai, chromadb, python-dotenv.

Funcionamiento:

    Carga citas filosóficas desde citas.py (con autor incluido).

    Genera embeddings usando el modelo text-embedding-3-small de OpenAI.

    Indexa las citas en una base vectorial local con ChromaDB.

    Recibe una frase del usuario, genera su embedding y busca las citas más similares.

    Usa GPT-4 para generar una respuesta basada en esas citas como contexto.
se necesita crear un archivo .env con tu api_key

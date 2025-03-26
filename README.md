# Lucas Rotelli Raulino - API de Desenvolvedor
**Versão**: v1.0 (Jornalista & Estudante em Desenvolvimento)

## Descrição
Jornalista e estudante de Análise e Desenvolvimento de Sistemas. Desenvolvo soluções web com HTML, CSS e JavaScript, além de atuar com análise de dados e projetos digitais. Especialista em SEO, WordPress, otimização de sites e monetização. Apaixonado por tecnologia, adapto-me rápido e entrego resultados de alta performance.

## Endpoints

### GET /sobre
Retorna informações pessoais.  
**Resposta**:  
`{ "nome": "Lucas Rotelli Raulino", "objetivo": "Criar soluções web e digitais de impacto", "local": "Espírito Santo do Pinhal, São Paulo, Brasil" }`

### GET /habilidades
Lista competências técnicas e profissionais.  
**Resposta**:  
`{ "skills": ["HTML5", "CSS3", "JavaScript", "SEO com IA", "WordPress", "Análise de Dados"], "nível": "Intermediário-Avançado" }`

### GET /experiencia
Retorna histórico profissional.  
**Resposta**:  
`{ "cargo": "Programador Web & Jornalista", "empresa": "Portal de Pinhal", "periodo": "Julho 2017 - Presente (7 anos e 9 meses)", "local": "Espírito Santo do Pinhal, SP", "atividades": ["Desenvolvimento web", "SEO", "Otimização de sites", "Monetização"] }`

### GET /formacao
Retorna formação acadêmica e certificações.  
**Resposta**:  
`{ "curso": "Análise e Desenvolvimento de Sistemas", "instituicao": "Unyleya", "periodo": "Janeiro 2025 - Julho 2027", "status": "Em andamento", "certificacoes": ["Fundamentos de WordPress", "SEO with AI"] }`

### GET /projetos
Lista projetos realizados (adapte com exemplos reais).  
**Resposta**:  
`{ "projetos": ["Desenvolvimento do Portal de Pinhal (HTML/CSS/JS)", "Otimização SEO para sites locais"], "links": "https://github.com/lucasrotelli92" }`

### POST /contato
Envia uma mensagem para o desenvolvedor.  
**Body**:  
`{ "email": "lucasrotelli92@gmail.com", "linkedin": "https://www.linkedin.com/in/lucasrotelliraulino" }`

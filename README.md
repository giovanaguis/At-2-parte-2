# At-2-parte-2
Trabalho
Cadastro
<!-- CONTEÚDO -->
    <main>

        <section class="form-secao">

            <div class="form-cartao">

                <form id="formCadastro">

                    <div class="campo">
                        <label for="nome">Nome completo</label>
                        <input type="text" id="nome" name="nome" placeholder="Digite seu nome" required>
                    </div>

                    <div class="campo">
                        <label for="email">E-mail</label>
                        <input type="email" id="email" name="email" placeholder="seuemail@exemplo.com" required>
                    </div>

                    <div class="campo">
                        <label for="senha">Senha</label>
                        <input type="password" id="senha" name="senha" placeholder="Crie uma senha" required minlength="6">
                    </div>

                    <div class="campo">
                        <label for="confirmarSenha">Confirmar senha</label>
                        <input type="password" id="confirmarSenha" name="confirmarSenha" placeholder="Repita a senha" required minlength="6">
                    </div>

                    <div class="campo campo-checkbox">
                        <input type="checkbox" id="termos" name="termos" required>
                        <label for="termos" style="margin-bottom: 0;">Eu concordo com os termos de uso</label>
                    </div>

                    <button type="submit" class="botao-enviar">Criar conta</button>

                    <div class="form-sucesso" id="cadastroSucesso">
                        ✅ Cadastro realizado com sucesso! Bem-vindo(a).
                    </div>

                </form>

            </div>

        </section>

    </main>

 Contato.html

    <!-- CONTEÚDO -->
    <main>

        <!-- INFORMAÇÕES DE CONTATO -->
        <section class="info-contato">

            <div class="info-contato-item">
                <div class="card-icone">📍</div>
                <h3>Endereço</h3>
                <p>Av. Paulista, 1000 - São Paulo, SP</p>
            </div>

            <div class="info-contato-item">
                <div class="card-icone">📞</div>
                <h3>Telefone</h3>
                <p>(11) 99999-9999</p>
            </div>

            <div class="info-contato-item">
                <div class="card-icone">✉️</div>
                <h3>E-mail</h3>
                <p>contato@meusite.com</p>
            </div>

            <div class="info-contato-item">
                <div class="card-icone">🕒</div>
                <h3>Horário</h3>
                <p>Seg a Sex, 9h às 18h</p>
            </div>

        </section>

        <!-- FORMULÁRIO -->
        <section class="form-secao">

            <div class="form-cartao">

                <form id="formContato">

                    <div class="campo">
                        <label for="nomeContato">Nome</label>
                        <input type="text" id="nomeContato" name="nome" placeholder="Digite seu nome" required>
                    </div>

                    <div class="campo">
                        <label for="emailContato">E-mail</label>
                        <input type="email" id="emailContato" name="email" placeholder="seuemail@exemplo.com" required>
                    </div>

                    <div class="campo">
                        <label for="mensagemContato">Mensagem</label>
                        <textarea id="mensagemContato" name="mensagem" placeholder="Escreva sua mensagem" required></textarea>
                    </div>

                    <button type="submit" class="botao-enviar">Enviar mensagem</button>

                    <div class="form-sucesso" id="contatoSucesso">
                        ✅ Mensagem enviada! Retornaremos em breve.
                    </div>

                </form>

            </div>

        </section>

        <!-- MAPA -->
        <div class="mapa-wrapper">
            <iframe
                src="https://www.google.com/maps?q=Avenida+Paulista,+São+Paulo,+SP&output=embed"
                allowfullscreen=""
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade"
                title="Mapa de localização">
            </iframe>
        </div>

    </main>

História
<!-- CONTEÚDO -->
    <main>

        <p class="sobre-intro">
            Uma linha do tempo com os marcos mais importantes da nossa jornada até aqui.
        </p>

        <!-- TIMELINE -->
        <div class="timeline">

            <div class="timeline-item">
                <span class="timeline-ano">2023</span>
                <h3>A ideia nasce</h3>
                <p>Tudo começou como um projeto simples de estudo, só pra aprender HTML e CSS na prática.</p>
            </div>

            <div class="timeline-item">
                <span class="timeline-ano">2024</span>
                <h3>Primeira versão no ar</h3>
                <p>A primeira versão da página foi publicada, ainda bem básica, sem modo escuro e sem estilo.</p>
            </div>

            <div class="timeline-item">
                <span class="timeline-ano">2025</span>
                <h3>Chega o modo escuro</h3>
                <p>Adicionamos o alternador de tema, cards, animações e deixamos tudo mais interativo.</p>
            </div>

            <div class="timeline-item">
                <span class="timeline-ano">2026</span>
                <h3>Novas páginas e recursos</h3>
                <p>Carrossel, vídeo, música, formulário de contato com mapa e muito mais chegaram para deixar tudo completo.</p>
            </div>

        </div>

    </main>

Sobre
    <!-- CONTEÚDO -->
    <main>

        <p class="sobre-intro">
            Somos um pequeno projeto feito com HTML, CSS e JavaScript puro, criado para mostrar
            que dá pra construir algo bonito, funcional e com modo escuro sem depender de frameworks pesados.
        </p>

        <!-- VALORES -->
        <section class="valores">

            <div class="card">
                <div class="card-icone">🎯</div>
                <h3>Missão</h3>
                <p>Entregar experiências simples, rápidas e acessíveis para qualquer pessoa que acesse a página.</p>
            </div>

            <div class="card card-destaque">
                <div class="card-icone">🔭</div>
                <h3>Visão</h3>
                <p>Ser referência em design limpo e código organizado, mesmo em projetos pequenos.</p>
            </div>

            <div class="card">
                <div class="card-icone">💛</div>
                <h3>Valores</h3>
                <p>Transparência, simplicidade e um carinho especial pelos detalhes.</p>
            </div>

        </section>

        <!-- TAGS -->
        <div class="tags">
            <span class="tag">#Sobre</span>
            <span class="tag">#Time</span>
            <span class="tag tag-destaque">#FeitoComCarinho 💛</span>
            <span class="tag">#CódigoLimpo</span>
        </div>

    </main>

# tela_WhatsApp
tela de WhatsApp para atendimento 
baixe a extensao do google https://www.webmobilefirst.com/en/
tela de login https://www.brasilcode.com.br/formulario-de-login-urso-animado-feito-com-html-css-e-js/



muda o style de aberto e fechado 
<div class="col-12 col-md-3 col-lg-2 mb-4 text-center lateral-col"> == para deixa perto do canto da tela
        <div class="espacamento"> == para a margim 
<div class="search-section p-3 mb-4 shadow rounded">
            <form class="d-flex flex-column" role="search">
              <input class="form-control mb-3" type="search" placeholder="Pesquisar conversas" aria-label="Search">
            </form>
            <button type="button" class="btn btn-outline-primary btn-block mb-2 btn-sm">Abertas</button>
            <button type="button" class="btn btn-outline-primary btn-block mb-2 btn-sm">Fechadas</button>
          </div>

          
.search-section, .contact-sidebar, .tab-section {
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  background-color: #ffffff; /* Adiciona cor de fundo */
}


contatos
<div class="contact-sidebar">
            <div class="contact-header">
              <h5>Contatos</h5>
            </div>
            <div class="contact-list">
              <div class="contact-item" v-for="contact in contacts" :key="contact.name">
                <img :src="contact.img" :alt="'Foto de ' + contact.name" class="contact-img">
                <span class="contact-name">{{ contact.name }}</span>
              </div>
            </div>
          </div>


          .search-section, .contact-sidebar, .tab-section {
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  background-color: #ffffff; /* Adiciona cor de fundo */
}

.contact-item:hover {
  background-color: rgba(13, 110, 253, 0.1);
}

.contact-name {
  margin-left: 10px; /* Espaçamento entre imagem e nome */
}

.contact-img {
  border-radius: 50%;
}

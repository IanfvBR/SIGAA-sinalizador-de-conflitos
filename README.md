<h1> SIGAA - sinalizador de conflitos</h1>
<p> Um add-on que automaticamente sinaliza conflitos de horários durante o processo de matrícula/rematrícula em disciplinas.
 Projetado para sistemas que utilizam a plataforma SIGAA, e testado no SIGAA da UFRN. Por esse motivo, é possível que não funcione ou apresente bugs em sites de outras universidades.</p>

 <h2> Como funciona?</h2>
 <p> Ao clicar no ícone do add-on, o background-script injeta o content-script na página HTML</p>
 <p> O content-script lê todas as disciplinas e turmas dentro da tabela, salvando elas numa lista de todos.</p>
 <p> Quando um checkbox é marcado ou desmarcado, a turma é salva ou removida da lista de selecionados.</p>
 <p> Sempre que há alguma alteração, as listas de todos e de selecionados são comparadas, checando por conflitos de horários, e então atualiza as mensagens se há ou não conflito de horário.</p>

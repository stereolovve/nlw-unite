//obj js
const participante = {
  nome: "Lucas",
  email: "lucas@gmail.com",
  dataInscricao: new Date(2024, 2, 22, 19, 20),
  dataCheckIn: new Date(2024, 2, 25, 22, 00)
}
//array
let participantes = [
  {
nome: "Lucas",
email: "lucas@gmail.com",
dataInscricao: new Date(2024, 2, 22, 19, 20),
dataCheckIn: new Date(2024, 2, 25, 22, 00) 
  }
]
/////estrutura de repetição loop, para cada participante que estiver registrado, ele busca um apos o outrou ate completar a lista
/const atualizarLista = (participantes) => {
  let output = ""
  //estrutura de repetição - loop: sempre vai rodar ate acabar
  for(let participante of participantes){
      output = output + criarNovoParticipante(participante)
  }/
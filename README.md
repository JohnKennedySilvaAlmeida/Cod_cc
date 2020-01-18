# Cod_cc
Projeto web - --- ** --- 

exe 1

Criar uma tela de login de usuários, aonde também é possível cadastrar um novo usuário no sistema.
Deve ter como informação:

    usuário
    senha
    nome

O usuário deve ser único no sistema.
Deve ser criado um programa em C para fazer o cadastro, a edição e listagem dos dados na tabela. Este programa deverá ser chamado no PHP para executar as funcionalidades do sistema.

----------------cods----------------------- base---
#include <stdio.h>

int main(){
    
    int senha;
    
    printf("Entre com a senha : ");
    scanf("%d",&senha);
    
    if(senha==123) {
        printf("Bem vindo admin \n\n");
    }else {
        printf("Senha enconrreta! \n\n");
        return main();
    }
    return (0);
} 
----------------- codigos ---  base -----------------------------------------------------------
https://forum.imasters.com.br/topic/468071-cadastro-e-login-em-c/


----------------------------------------------------------------------------------

exe 2

Criar uma jqgrid que liste os usuários já cadastrados no sistema.

Após logar, a página exibida deverá:

    Listar os usuários cadastrados (usando jqgrid) no sistema
    Ter uma opção para deslogar o usuário.

De preferência utilizar Bootstrap.
A tela deve buscar as informações em um programa em C que retorna os dados a serem listados.

--------------------------------------------------

exe 3 

Tela para edição de usuários
Apenas os campos de nome e senha poderão ser editados.

Deverá ser possível editar, apenas o usuário logado!

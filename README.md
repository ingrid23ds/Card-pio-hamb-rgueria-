import React from 'react';
import { SafeAreaView, Text, StyleSheet } from 'react-native';

const Menu = () => {
  return (
    <SafeAreaView style={styles.container}>
      <Text style={styles.title}>Cardápio de Hambúrgueres</Text>
      <Text style={styles.item}>1. Hambúrguer Clássico</Text>
      <Text style={styles.description}>Pão, hambúrguer de carne, queijo, alface, tomate, cebola, maionese e ketchup.</Text>
      <Text style={styles.item}>2. Hambúrguer Vegetariano</Text>
      <Text style={styles.description}>Pão, hambúrguer de grão de bico, queijo, alface, tomate, cebola, maionese vegana e ketchup.</Text>
      {/* Adicione mais itens de menu conforme necessário */}
    </SafeAreaView>
  );
};


const styles = StyleSheet.create({
  container: {
    flex: 1,
    paddingHorizontal: 20,
    paddingTop: 50,
    backgroundColor: '#000000', // cor do fundo para o SafeAreaView 
    
  },
  title: {
    fontSize: 24,
    fontWeight: 'bold',
    marginBottom: 20,
    color: '#ffff00', // cor do titulo 
  },

  item: {
    fontSize: 18,
    fontWeight: 'bold',
    marginBottom: 5,
    color: '#ffff00', // color dos itens 
  },
  description: {
    fontSize: 16,
    marginBottom: 15,
    color:'#ffffff', // cor da descrição 
  },
});

export default Menu;



<form action="process_payment.php" method="POST">
    <label for="cardholder">Nome do Titular:</label>
    <input type="text" id="cardholder" name="cardholder" required>

    <label for="cardnumber">Número do Cartão:</label>
    <input type="text" id="cardnumber" name="cardnumber" required>

    <label for="expiry">Data de Validade:</label>
    <input type="text" id="expiry" name="expiry" placeholder="MM/AA" required>

    <label for="cvv">Código de Segurança (CVV):</label>
    <input type="text" id="cvv" name="cvv" required>

    <label for="billing_address">Endereço de Cobrança:</label>
    <input type="text" id="billing_address" name="billing_address" required>

    <button type="submit">Pagar</button>
</form>

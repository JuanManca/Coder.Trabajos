# Coder.Trabajos

public class Usuario
{
	private int id;
	private string nombre;
	private string apellido;
	private string nombreUsuario;
	private string contraseña
	private string mail;
}

public class Producto
{
	private int id;
	private string descripcion;
	private double costo;
	private double precioVenta;
	private double stock;
	private int idUsuario;
}

public class ProductoVendido
{
	private int id;
	private int idProducto;
	private double stock;
	private int idVenta;
}

public class Venta
{
	private int id;
	private string comentarios;
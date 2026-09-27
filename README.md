# shop-management
package Shop.Services;

import java.time.LocalDate;

public class Product {
	private int id;
	private String name;
	private double price;
	private LocalDate mfgDate;
	private int stock;
	private LocalDate expireDate;
	private int expiryReminingDays;
	public int getId() {
		return id;
	}
	public void setId(int id) {
		this.id = id;
	}
	public String getName() {
		return name;
	}
	public void setName(String name) {
		this.name = name;
	}
	public double getPrice() {
		return price;
	}
	public void setPrice(double price) {
		this.price = price;
	}
	public LocalDate getMfgDate() {
		return mfgDate;
	}
	public void setMfgDate(LocalDate mfgDate) {
		this.mfgDate = mfgDate;
	}
	public int getStock() {
		return stock;
	}
	public void setStock(int stock) {
		this.stock = stock;
	}
	public LocalDate getExpireDate() {
		return expireDate;
	}
	public void setExpireDate(LocalDate expireDate) {
		this.expireDate = expireDate;
	}
	public int getExpiryReminingDays() {
		return expiryReminingDays;
	}
	public void setExpiryReminingDays(int expiryReminingDays) {
		this.expiryReminingDays = expiryReminingDays;
	}
	
	public String toString() {
		return "Product [id=" + id + ", name=" + name + ", price=" + price + ", mfgDate=" + mfgDate + ", stock=" + stock
				+ ", expireDate=" + expireDate + ", expiryReminingDays=" + expiryReminingDays + "]";
	}
	public Product() {
		super();
		
	}
	public Product(int id, String name, double price, LocalDate mfgDate, int stock, LocalDate expireDate,
			int expiryReminingDays) {
		super();
		this.id = id;
		this.name = name;
		this.price = price;
		this.mfgDate = mfgDate;
		this.stock = stock;
		this.expireDate = expireDate;
		this.expiryReminingDays = expiryReminingDays;
	}
	
	
	
}


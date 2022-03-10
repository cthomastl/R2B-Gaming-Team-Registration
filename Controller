package application;

import java.io.IOException;

import javafx.event.ActionEvent;
import javafx.fxml.FXML;
import javafx.fxml.FXMLLoader;
import javafx.scene.Node;
import javafx.scene.Parent;
import javafx.scene.control.Button;
import javafx.scene.control.Label;
import javafx.scene.control.TextField;
import javafx.stage.Stage;

public class Controller {

	@FXML
private Label myLabel;
	@FXML
private TextField myTextField;
	@FXML
private TextField myTextField2;
	@FXML
private TextField myTextField3;
	@FXML
	private Button myButton;
	
	String name;
	int age;
	String console;
	boolean submit;

	
	public void submit(ActionEvent event) {
		name = myTextField.getText();
		console = myTextField3.getText();
		System.out.println(name);
		System.out.println(console);
		
		
		
		try {
		age = Integer.parseInt(myTextField2.getText());
		System.out.println(age);
		
			if(age >=18) {
				myLabel.setText("Registration Successfull!");
				submit = true;
				System.out.println(submit);
			}
			else {
				myLabel.setText("Must be over 18");
				
			}
		}
		catch (NumberFormatException e) {
			myLabel.setText("Invalid Input");
			myTextField2.setText("");
		}
		catch (Exception e) {
			System.out.println(e);
			myLabel.setText("error");
			
		
			
		}
		if (submit == true) {
			myTextField.setText(" ");
			myTextField2.setText(" ");
			myTextField3.setText(" ");
			
		
				
			}
	
			
		}
		
}

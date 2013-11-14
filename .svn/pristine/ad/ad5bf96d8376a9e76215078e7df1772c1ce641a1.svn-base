/*
 * To change this template, choose Tools | Templates
 * and open the template in the editor.
 */

package models;
import java.util.*;
import javax.persistence.*;
import play.data.format.*;
import play.data.validation.*;
import play.db.jpa.*;

/**
 *
 * @author AlvaroTai
 */
public class Persona {
    @Id
    @Constraints.Required
    public Integer numPersona;
     @Constraints.Required
    public String nonmbres;
     @Constraints.Required
    public String apellidos;
     @Constraints.Required
    public String docIdentidad;
    @Transient
    @Formats.DateTime(pattern="yyyy-MM-dd")
    public Date fechaNacimiento;
    public String direccion;
}

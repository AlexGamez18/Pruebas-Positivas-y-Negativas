# Pruebas-Positivas-y-Negativas
# Prueba 1 - ClientesTest
package tienda_level.sshop;

import org.junit.After;
import org.junit.AfterClass;
import org.junit.Before;
import org.junit.BeforeClass;
import org.junit.Test;
import static org.junit.Assert.*;

/**
 *
 * @author Irma
 */
public class ClientesTest {
    
    public ClientesTest() {
    }
    
    @BeforeClass
    public static void setUpClass() {
    }
    
    @AfterClass
    public static void tearDownClass() {
    }
    
    @Before
    public void setUp() {
    }
    
    @After
    public void tearDown() {
    }

    /**
     * Test of setNombre method, of class Clientes.
     */
    @Test
    public void testSetNombre() {
        System.out.println("setNombre");
        String _Nombre = "";
        Clientes instance = new Clientes();
        instance.setNombre(_Nombre);    
    }

    /**
     * Test of getNombre method, of class Clientes.
     */
    @Test
    public void testGetNombre() {
        System.out.println("getNombre");
        Clientes instance = new Clientes();
        String expResult = "";
        String result = instance.getNombre();
        assertEquals(expResult, result);
    }

    /**
     * Test of setApellidos method, of class Clientes.
     */
    @Test
    public void testSetApellidos() {
        System.out.println("setApellidos");
        String _Apellidos = "";
        Clientes instance = new Clientes();
        instance.setApellidos(_Apellidos);
    }

    /**
     * Test of getApellidos method, of class Clientes.
     */
    @Test
    public void testGetApellidos() {
        System.out.println("getApellidos");
        Clientes instance = new Clientes();
        String expResult = "";
        String result = instance.getApellidos();
        assertEquals(expResult, result);
    }

    /**
     * Test of setDui method, of class Clientes.
     */
    @Test
    public void testSetDui() {
        System.out.println("setDui");
        String _Dui = "";
        Clientes instance = new Clientes();
        instance.setDui(_Dui);
    }

    /**
     * Test of getdui method, of class Clientes.
     */
    @Test
    public void testGetdui() {
        System.out.println("getdui");
        Clientes instance = new Clientes();
        String expResult = "";
        String result = instance.getdui();
        assertEquals(expResult, result);

    }
    
}
# Prueba 2 - FacturaciónTest
package tienda_level.sshop;

import org.junit.After;
import org.junit.AfterClass;
import org.junit.Before;
import org.junit.BeforeClass;
import org.junit.Test;
import static org.junit.Assert.*;

/**
 *
 * @author Irma
 */
public class FacturacciónTest {
    
    public FacturacciónTest() {
    }
    
    @BeforeClass
    public static void setUpClass() {
    }
    
    @AfterClass
    public static void tearDownClass() {
    }
    
    @Before
    public void setUp() {
    }
    
    @After
    public void tearDown() {
    }

    /**
     * Test of getNombre method, of class Facturacción.
     */
    @Test
    public void testGetNombre() {
        System.out.println("getNombre");
        Facturacción instance = null;
        String expResult = "";
        String result = instance.getNombre();
        assertEquals(expResult, result);
    }

    /**
     * Test of setNombre method, of class Facturacción.
     */
    @Test
    public void testSetNombre() {
        System.out.println("setNombre");
        String Nombre = "";
        Facturacción instance = null;
        instance.setNombre(Nombre);
    }

    /**
     * Test of getApellido method, of class Facturacción.
     */
    @Test
    public void testGetApellido() {
        System.out.println("getApellido");
        Facturacción instance = null;
        String expResult = "";
        String result = instance.getApellido();
        assertEquals(expResult, result);
    }

    /**
     * Test of setApellido method, of class Facturacción.
     */
    @Test
    public void testSetApellido() {
        System.out.println("setApellido");
        String Apellido = "";
        Facturacción instance = null;
        instance.setApellido(Apellido);
    }

    /**
     * Test of getNumeroCaja method, of class Facturacción.
     */
    @Test
    public void testGetNumeroCaja() {
        System.out.println("getNumeroCaja");
        Facturacción instance = null;
        int expResult = 0;
        int result = instance.getNumeroCaja();
        assertEquals(expResult, result);
    }

    /**
     * Test of setNumeroCaja method, of class Facturacción.
     */
    @Test
    public void testSetNumeroCaja() {
        System.out.println("setNumeroCaja");
        int NumeroCaja = 0;
        Facturacción instance = null;
        instance.setNumeroCaja(NumeroCaja);
    }

    /**
     * Test of getTotal method, of class Facturacción.
     */
    @Test
    public void testGetTotal() {
        System.out.println("getTotal");
        Facturacción instance = null;
        double expResult = 0.0;
        double result = instance.getTotal();
        assertEquals(expResult, result, 0.0);
    }

    /**
     * Test of setTotal method, of class Facturacción.
     */
    @Test
    public void testSetTotal() {
        System.out.println("setTotal");
        double Total = 0.0;
        Facturacción instance = null;
        instance.setTotal(Total);
    }

    /**
     * Test of verDatos method, of class Facturacción.
     */
    @Test
    public void testVerDatos() {
        System.out.println("verDatos");
        Facturacción instance = null;
        String expResult = "";
        String result = instance.verDatos();
        assertEquals(expResult, result);
    }
    
}
# Prueba 3 - TiendaLevelShopTest
package tienda_level.sshop;

import org.junit.After;
import org.junit.AfterClass;
import org.junit.Before;
import org.junit.BeforeClass;
import org.junit.Test;

/**
 *
 * @author Irma
 */
public class Tienda_LevelSShopTest {
    
    public Tienda_LevelSShopTest() {
    }
    
    @BeforeClass
    public static void setUpClass() {
    }
    
    @AfterClass
    public static void tearDownClass() {
    }
    
    @Before
    public void setUp() {
    }
    
    @After
    public void tearDown() {
    }

    /**
     * Test of main method, of class Tienda_LevelSShop.
     */
    @Test
    public void testMain() {
        System.out.println("Datos");
        String[] args = null;
        Tienda_LevelSShop.main(args);
    }
    
}

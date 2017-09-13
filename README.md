// hello-world
function mytest1() {
    var frame = new javax.swing.JFrame( "hello" );
    var panel = new javax.swing.JPanel();
    var label = new javax.swing.JLabel();
    label.setText( "Hello" );
    panel.setLayout( new java.awt.BorderLayout() );
    panel.add( label, java.awt.BorderLayout.CENTER );
    frame.setLayout( new java.awt.BorderLayout() );
    frame.add( panel, java.awt.BorderLayout.CENTER );
    frame.setSize( 100, 100 );
    frame.setDefaultCloseOperation( javax.swing.JFrame.DISPOSE_ON_CLOSE );
    frame.setVisible( true );
}
mytest1();

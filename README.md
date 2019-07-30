Curl Class for CodeIgniter 3

1.  Add this Class into your Library folder.

2.  Load library to your Controller or other files.

3.  Standard example:
    $this->load->library('curl');                 // load library
    $this->curl->set_url('http://localhost/api'); // api url
    $CI->curl->set_params($params);               // any array
    $CI->curl->set_method($method);               // get, post, put or delete

    $result = $CI->curl->result();                // get result
    
    
    
ENJOY!


===
Saka Mahendra Arioka
w: https://www.sakarioka.com
e: saka@sakarioka.com

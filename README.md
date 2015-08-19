# cryptex #

cryptex is a collection of simple command-line encryption tools. Before using these scripts, edit them
to make sure the file references point to the correct places.

## Usage ##
encode-records: encode all plaintext records in RECORD_DIR.
decode-records: decode all encrypted records in RECORD_DIR.
filter-record-blob <record_name>: decrypt the blob file in RECORD_DIR and output the record
corresponding to <record_name>.
